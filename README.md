# Choose Your Own Adventure - The Allegory of the Cave

## Description

This project is a web-based interactive story inspired by the concept of "Choose Your Own Adventure" (COYA) books and Plato’s Allegory of the Cave. It also allows the user to make decisions at different points, leading to multiple possible paths and three different endings: a good ending, a neutral ending, and a bad ending.

Watch the video demonstration here:
[Click here to watch the video on YouTube](https://youtu.be/-qGIrwAaH5k)

## Project Structure

The project contains:

- 11 HTML files
- An `index.html` file as the starting point
- Multiple decision-based pages connected using HTML `<a>` links
- Three clearly defined endings

Each HTML file includes:
- `<head>`, `<body>`, and `<footer>` sections
- At least one heading (`<h1>` or `<h2>`)
- At least one paragraph (`<p>`)
- At least one image (`<img>`)
- Text formatting elements such as `<b>`, `<strong>`, or `<small>`
- At least two decision links

---

## Technologies Used

- HTML5
- NGINX (local server)
- WSL (Ubuntu)

---

## How to Run the Project

### 1. Make sure NGINX is installed and running.

Check NGINX status:

```bash
sudo systemctl status nginx
```

Start NGINX if necessary:

```bash
sudo systemctl start nginx
```

### 2. Move project files to the NGINX directory

```bash
sudo mkdir -p /var/www/html/adventure
sudo cp -r ~/lab2/* /var/www/html/adventure/
sudo chmod -R 755 /var/www/html/adventure
```

### 3. Open in your browser:

```bash
http://localhost/adventure/
```

The game starts from index.html.
