# django_rentsite
Rent site by Django with admin panel

# create virtual env

```bash
python3 -m venv ./venv
```
If error will throw, we need to install

```bash
sudo apt-get install python3-venv
```
# Activate venv

```bash
source ./venv/bin/activate
```
# Deactivate venv

```bash
deactivate
```
# Django-cli

```bash
django-admin help
```
# Craete project

```bash
django-admin startproject rentsite .
```

# App Requirements:

FRONTEND PAGES

    • Home
    • About
    • Listings
    • Single Listing
    • Search
    • Register
    • Login
    • Dashboard (Inquiries)

DESIGN SPECS
    • Use BTRE logo (Frontend and admin)
    • Branding colors – blue(#10284e) green(#30caa0)
    • Mobile Friendly
    • Social media icons & contact info
    • Doesn’t have to be too fancy but must be clean


FUNCTIONALITY SPECS
    • Manage listings, realtors, contact inquiries and website users via admin
    • Role based users (staff and non-staff)
    • Display listings in app with pagination
    • Ability to set listings to unpublished
    • Search listings by keyword, city, state, bedrooms and price (Homepage & search page)
    • List realtors on about page with “seller of the month” (Control via admin)
    • Listing page should have fields listed below
    • Listing page should have 5 images with lightbox
    • Lightbox should scroll through images
    • Listing page should have a form to submit inquiry for that property listing
    • Form info should go to database and notify realtor(s) with an email
    • Frontend register/login to track inquiries
    • Both unregistered and registered users can submit form. If registered, can only submit one per listing



LISTING PAGE FIELDS

    • Title
    • Address, city, state, zip
    • Price
    • Bedrooms
    • Bathrooms
    • Square Feet
    • Lot Size
    • Garage
    • Listing Date
    • Realtor – Name & Image
    • Main image and 5 other images

Possible Future Functionality
    • Google maps on listing page
    • Buyer testimonials