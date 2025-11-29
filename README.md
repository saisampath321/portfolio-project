# 📁 Portfolio Website Project

A simple and clean **static portfolio website** built using **HTML &
CSS**, designed for beginners in **Cloud & DevOps** to practice hosting
on AWS services such as **S3** and **EC2**.

## 🚀 Project Overview

This project contains a basic personal portfolio website with the
following sections: - **About Me** - **Projects** - **Simple Layout &
Styling** - **Responsive Structure**

It is ideal for: - Hosting on **Amazon S3** (Static Website Hosting) -
Hosting on **Amazon EC2** with Apache - Practicing Linux, Git, and AWS
fundamentals

## 📦 Project Structure

    portfolio_project/
    │── index.html        # Main webpage
    │── style.css         # Styling for the website

## 🛠️ Technologies Used

-   **HTML5**
-   **CSS3**
-   **Linux Commands**
-   **Git & GitHub**
-   **AWS EC2 / S3**

## ☁️ Deployment Guide (EC2)

1.  Install Apache:

    ``` bash
    sudo yum install httpd -y
    sudo systemctl start httpd
    sudo systemctl enable httpd
    ```

2.  Clone the GitHub repo:

    ``` bash
    git clone https://github.com/YOUR_USERNAME/portfolio-project.git
    ```

3.  Move files:

    ``` bash
    sudo mv portfolio-project/* /var/www/html/
    sudo systemctl restart httpd
    ```

## ☁️ Deployment Guide (S3)

1.  Upload files to S3\
2.  Enable static hosting\
3.  Make objects public\
4.  Access via S3 website endpoint

## Link
http://3.26.255.41/

## 📄 License

Open-source project.

## 🙌 Author

**sai sampath**\
Cloud & DevOps Enthusiast
