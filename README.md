# Ansible Playbook

## Installing Requirements

Order matters for this step!

```
sudo apt-get install apache2
```

## Setting up the HTML

Apache files live in /var/www/html/. Lets quickly get there. Make sure you're in your root directory first, cd, then cd /var/www/html/.

This html directory is where all your website files will live. Lets quickly make a simple Hello World file.

Using your favorite text editor, type the following in

```
<!DOCTYPE html>
<html>
<head>
    <title>Hello World!</title>
</head>
<body>
    <h1>Hello World!</h1>
</body>
</html>
```
