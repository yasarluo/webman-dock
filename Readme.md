# Set environment variables
Copy file **env-example** to **.env**, and change the item what you need.

Change the **HOST_APP_DIR** env item, ensure where your webman app is. 

# Build image
Ensure you have install docker and docker-compose first.

You can build you image by execute follow command:

> **docker-compose up -d webman**

# Run
Enter the container:
> **docker-compose exec webman bash**

If you havn't init composer, you can run this command:
> **composer install**

Run in front: 
> **php start.php start**

Run in backend:
> **php start.php start -d**