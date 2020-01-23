# Open Digital Delivery Foundation Web

This repository contains the source for the website for the Open Digital Delivery Foundation (ODDF), deployed at https://opendigitaldelivery.org

## Running Locally

The ODDF site is developed using Jekyll. To preview the contents locally, clone this repo and run the following command on your local machine (Docker required). 

```bash
 docker run --rm -it -p 4000:4000 --volume="$PWD:/srv/jekyll" jekyll/jekyll:3.8 jekyll serve
 ```
