Hello Bro, I am Sujal, writing this. If you have questions: call on +91 9511776733

# Lets Start

## Step 1:

    - Download Xampp Server from https://www.apachefriends.org/
    - Install and start the server

## Step 2:

    - Now download and extract this source code file.
    - Copy and Paste the whole file to > C:/Xampp/htdocs

## Step 3:

    - Since the Xampp App is already running Start these two services in it > (see xampp.png) for reference
    - Now website is up and running

## Step 4:

    - Go to http://localhost
    - and Click on "phpMyAdmin" link in top bar > (see localhostpage.png) for reference
    - then click on "New" in the left bar
    - at the Database name enter "job_portal"
    - and click create > (see CreateDatabase.png) for refrence
    - Now select job_portal in the side panel > (see SelectJobPortal.png) for refrence
    - Now click on choose files and select this file =>> c:/xampp/htdocs/OnlineJobPortal/Database/job_portal.sql
    - Scroll down and click Import

## Step 5:

    - Go to http://localhost/OnlineJobPortal/System/
    - You will see the website up and running

# What you can

-- User can Login/Register

-- User can post job as an employer
-- User can apply to job as an employee

-- Companies can make account and update profile

# Add data

## Through Website frontend

### Use website to update backend data

## Through Backend

### go to http://localhost/phpmyadmin/ and select job_portal from sidebar

### below job_portal you will find these fields

#### tbl_countries

#### tbl_alerts

#### tbl_acedamic_qualifications

#### tbl_categories

#### tbl_experience

#### tbl_jobs

#### tbl_job_applications

#### tbl_language

#### tbl_other_attachments

#### tbl_professional_qualifications

#### tbl_referers

#### tbl_tokens

#### tbl_trainings

#### tbl_users

These are tables and have data of he name they are given.
If you want to add/edit/remove users edit tbl_users table and so on.
