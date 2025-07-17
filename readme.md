# Minecraft Server Status Page

A minimal single-file HTML page that displays the status of a Minecraft server by fetching its MOTD (Message of the Day) using the [mcstatus.io](https://api.mcstatus.io) API.

![Preview](https://i.ibb.co/XkC37pBs/image.png)

## What It Does

- Fetches and displays the server's MOTD in real time  
- Uses `fetch` to query the API based on the IP and port  
- Clean, responsive design in a single HTML file (no external JS or setup needed)

## How to Use

1. Open `index.html` in any browser  
2. If you're using a different server, update the IP and port in the script section:

   ```js
   const serverIP = "hypixel.net";
