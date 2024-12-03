![Product Feed View in Popup](https://github.com/user-attachments/assets/08abacc7-849b-4480-bc4b-b22c44df5073)![Fetch Instagram Images](https://github.com/user-attachments/assets/cb580570-e292-467d-b902-42f1ff7a137a)# **Magento 2 Instagram Feed Extension**

Instagram is a powerful tool for visual engagement, and integrating Instagram feeds into your Magento 2 store can significantly enhance user experience and boost brand visibility. The **Magento 2 Instagram Feed Extension** from Meetanshi allows seamless integration of Instagram posts directly on your online store. This extension brings Instagram's dynamic and visual appeal to your eCommerce website, enabling your visitors to view your latest Instagram photos directly on your product pages.

## **How It Works**

The **Magento 2 Instagram Feed Extension** works by fetching and displaying your Instagram posts on your website in a customizable, responsive and attractive manner. It allows you to showcase your Instagram images in a grid or carousel format, encouraging user interaction and promoting your social media presence. The extension integrates smoothly with your existing Magento store, ensuring that the feed automatically updates with your latest Instagram content.

## **Key Features**

* Display Instagram photos on any CMS page of your website.  
* Retrieve images using your Instagram username or by selecting multiple hashtags.  
* Add interactive hotspots to the fetched Instagram images, which can be shown in a popup.

## **Lightweight and Responsive Display**

The **Instagram Feed for Magento 2** is optimized for both desktop and mobile devices, ensuring a fast, responsive and visually appealing display on any screen size. Its lightweight code guarantees seamless performance without slowing down your website. Additionally, the extension offers customizable display layouts, allowing you to choose between grid or carousel views to perfectly align with your store’s design and branding.

## **Choose Display Preferences**

The extension enables you to customize the appearance and functionality of the Instagram feed to suit your store’s requirements. You can select your preferred layout style, adjust the number of posts displayed and showcase posts tagged with specific Instagram hashtags to promote targeted products or campaigns. Choose between grid or carousel layouts to best fit your store’s design.

## **Social Proof for Products**

Displaying Instagram posts directly on product pages serves as powerful social proof, showcasing real-life images of your products used or reviewed by influencers and followers. This Instagram Feed extension allows you to leverage user-generated content to build trust, enhance the shopping experience and drive conversions. By featuring authentic images from your Instagram followers, you can boost engagement and drive more traffic to your Instagram account through your product pages.

## **Extension Installation**

To install the Magento 2 Instagram Feed Extension:

### **Step 1:**

Extract the zip file and upload the extension to the root directory of your Magento 2 installation using FTP.

### **Step 2:**

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush

## **How to setup Instagram feed to Magento 2**

To configure the Magento 2 Instagram Feed extension, follow these simple steps:

### **Step 1: Configure Settings**

To configure the extension, log in to your Magento 2 admin panel and navigate to **Stores \> Configuration \> Instagram**. Here, you can find various settings to enable and customize the extension.

* **Instagram**: Enable or disable the Instagram extension.  
* **Instagram Profile Username**: Enter your Instagram username to display in the image popup.  
* **Instagram User Access Token**: Provide your access token. Follow the steps below to obtain it.

### **Step 2: Connect Instagram Graph API**

Before proceeding, ensure you have the following prerequisites:

* An Instagram Business or Creator Account.  
* A Facebook Page connected to your Instagram account.  
* A Facebook Developer account with access to the Instagram page.  
* A registered Facebook App with Basic settings configured.

### **Step 3: Configure Page View Settings**

To display Instagram images on different pages of your site, configure the following settings:

![Configure Page View Settings](https://github.com/user-attachments/assets/a1b0c16f-2e26-43f4-af72-15314d86adfd)

* **Display Instagram Images on Home Page**: Select “YES” to show Instagram images on the home page.  
* **Number of Instagram Images to Display on Home Page**: Define how many images to display on the home page.  
* **Display Instagram Images on Category Page**: Select “YES” to show Instagram images on the category page.  
* **Number of Instagram Images to Display on Category Page**: Specify the number of images to display on the category page.  
* **Display Instagram Images on Product Page**: Select “YES” to show Instagram images on the product page.  
* **Number of Instagram Images to Display on Product Page**: Set the number of images to display on the product page.  
* **Display Images in Product Media Gallery**: Choose “YES” to display Instagram images in the Product Media Gallery.  
* **Display Images in Product Detail Section**: Select “YES” to show Instagram images in the Product Detail Section.  
* **Number of Instagram Images to Display on Instagram Page**: Set how many Instagram images you want to display on the Instagram page.

### **Step 4: Fetch Instagram Images**

![Fetch Instagram Images](https://github.com/user-attachments/assets/4d6c4695-935b-43a6-92b4-399acb6e59ea)

Click "Fetch New Images" to retrieve Instagram images based on the configured username or hashtag. You can review, approve or delete the fetched images as needed.

### **Step 5: Manage Instagram Images**

![Manage Instagram Images](https://github.com/user-attachments/assets/26772644-3104-451b-8746-972801c086b0)

All approved images are listed here. You can edit the image details, set hotspots, add captions, insert links and create product feeds, as configured in the extension settings.

### **Step 6: Caption with Hyperlink View Settings**

If you have configured the Instagram Popup View as “Caption with Hyperlink,” you can edit the image to add hotspots, captions and hyperlinks here. Simply drag and drop the pins to set the hotspots.

![Caption with Hyperlink View Settings](https://github.com/user-attachments/assets/f60f70cb-674c-49f9-b7d0-664dd6c63edd)

* **Caption-1**: Enter the caption that will redirect users when clicked in the popup.  
* **Hyperlink-1**: Provide the hyperlink to redirect users when they click the caption in the popup.  
* The **Hotspot Position X-1** and **Hotspot Position Y-1** will be automatically set when you position the pins.

You can configure up to 5 captions and hyperlinks for each Instagram image.

### **Step 7: Check Product Feed View Settings**

If you have configured the Instagram Popup View as "Product Feed," you can set up product feeds for the fetched images. Simply drag and drop the pins to position the hotspots and assign SKUs to each hotspot.

![Check Product Feed View Settings](https://github.com/user-attachments/assets/dcfb5bea-4b53-4f0f-bd4e-6910228a3e07)

* **Product SKU-1**: Enter the product SKU to display the product feed in the popup.  
* The **Hotspot Position X-1** and **Hotspot Position Y-1** will be automatically set once you place the pins.

You can set up to 5 product feeds for each image, with each hotspot linked to a specific product.

### **Step 8: Check Category-Specific Settings**

![Check Category-Specific Settings](https://github.com/user-attachments/assets/8e9e9a98-98fa-4e82-9c3a-df401e5c5035)

To display Instagram images on a specific category page, select the desired **Username** or **Hashtag** as shown below. This allows you to tailor the Instagram feed to match the category's content.

### **Step 9: Check Product-Specific Settings**

![Check Product-Specific Settings](https://github.com/user-attachments/assets/2e9de71b-7234-4475-93e5-93f9370e0272)

To display Instagram images on specific product pages, choose the desired **Username** or **Hashtag** as shown above.

### **Step 10: Check Instagram on the Frontend**

After configuring the extension, the Instagram feed will be displayed on various pages of your site, including:

* **Instagram Images on the Home Page**

![Instagram Images on the Home Page](https://github.com/user-attachments/assets/6caf8e9c-e746-4d8a-aeb4-122ed6399f91)

* **Instagram Images on Category Pages**

![Instagram Images on Category Pages](https://github.com/user-attachments/assets/03654330-fe07-43dc-a73b-4b0ba5d604d3)

* **Instagram Images on Product Page**

![Instagram Images on Product Page](https://github.com/user-attachments/assets/f4bc4315-eaca-4da8-adb5-90d1caa65c77)

* **Instagram Images on the Instagram Page**

![Instagram Images on the Instagram Page](https://github.com/user-attachments/assets/c25b583c-874f-4650-ad57-b4781b115b25)

You can access the Instagram page via the top or footer link. When you hover over an Instagram image, the like and comment counts are displayed. Clicking on an image will open a popup with the selected view, as configured.

* **Caption with Hyperlink View**

![Caption with Hyperlink View](https://github.com/user-attachments/assets/aa047e57-bd2e-4797-b9c1-f4853fa665c3)

When hovering over the Instagram image, hotspots will appear. As users hover over each hotspot, a caption will be displayed. Clicking the caption will redirect users to the specified link. Users can navigate through all images using the navigation arrows and click the "Follow" button to follow the Instagram account.

* ### **Product Feed View in Popup**

![Product Feed View in Popup](https://github.com/user-attachments/assets/c2a1528b-c881-435a-b2b6-a47c5e8e81dd)

In this view, users can hover over the hotspots on the images to see related product blocks. Clicking on a product block will redirect users to the corresponding product page.

## Download our [Magento 2 Instagram Feed](https://meetanshi.com/magento-2-instagram.html) Extension
