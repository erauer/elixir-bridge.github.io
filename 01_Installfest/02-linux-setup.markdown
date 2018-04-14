---
layout: page
title: Linux setup
date: 2018-04-11 10:16:00 -0700
---


## Linux

These steps apply to **Ubuntu Linux** only. If you are using some other flavor of Linux, get help from a TA.

You will need sudo access in order to complete these directions (The first user account has this by default)

### Step 1: Open a terminal

Open a terminal (Applications > Accessories > Terminal). You may want to right-click on the terminal icon and select "Add to panel" so the icon will appear next to the default help and Firefox icons in the top panel.

Type this in the terminal:

```text
sudo apt-get update
```

### Step 2: Install Tasksel

Type this in the terminal:

```text
sudo apt-get install tasksel
```

### Step 3: Install Postgres

Type this in the terminal:

```text
sudo tasksel install postgresql-server
```

In order to start Postgres, type this into the terminal:

```text
sudo systemctl start postgresql
```
