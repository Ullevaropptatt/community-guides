# Setting a Server Header Image in Rust

**Author:** .viperrust

This guide will walk you through the process of setting a custom header image for your Rust server using the **Config Editor**. The header image is displayed in the server browser and helps make your server stand out.

## Requirements

Before proceeding, make sure you have:

* Access to your Rust server's **Config Editor**
* A **direct link** to your header image (e.g., from PostImage, Imgur, or another image host)
* An image sized **512x256 pixels** (recommended for best display)

## Step Process

### 1. Open Your Server’s Config Editor
- Navigate to your Rust server's control panel.
- Locate and open the **Config Editor**.

### 2. Add a New Setting
- In the **Config Editor**, create a new setting by entering the following:
  - **Key**: `server.headerimage`
  - **Value**: Your image link (e.g., `https://i.postimg.cc/85SOR0nV/512x256.jpg`)

### 3. Save the Setting
- After entering the key and value, click **Add Setting** to save the change.

### 4. Restart Your Rust Server
- To apply the changes, restart your Rust server. The new header image will now be displayed in the server browser.

