# CyberManipal

If you like technology, and especially cybersecurity like everyone at [Manipal Information Security Team](https://wearemist.in/), you'd love it at [CyberManipal](https://cybermanipal.wearemist.in). It is open for all, regardless of whether or not one is part of the club. Here are some important links for the same.
- [Become a writer](bit.ly/cybermanipal-author)
- [Editorial Policy](https://cybermanipal.wearemist.in/editorialpolicy)

CyberManipal even has a weekly newletter with a round-up of what is happening in the tech world, curated for tech enthusiasts! Subscribe to the newsletter [here](https://cybermanipal.wearemist.in/#subscribe)

# Maintenance guide for the website
This app is written in NextJS, for the cybersecurity news page [CyberManipal](https://cybermanipal.wearemist.in) maintained by [Manipal Information Security Team](https://wearemist.in/). Here are a few guidelines you will need to follow for the handling of the website.

## Hosting the website
The latest copy of the code is stored on [this repository](https://github.com/ManipalInformationSecurityTeam/cybermanipal). If you need to redeploy, or change hosting, use this repository so that it would be easier to maintain in the future. The current website is hosted on Vercel, but it can be changed if you are more comfortable with some other platform. The good thing about Vercel is that it will automatically redeploy if you push changes to your repository. 

You will need to set up the environment variables on your hosting platform so that the app works properly. Refer to [example.env.local](https://github.com/Parthiv-M/cybermanipal/blob/main/example.env.local) for the required enviroment variables. This file needs to be saved as `.env.local`, or if the hosting service allows you to save these environment variables in the dashboard itself, you could ignore creating that file. This file needs to be kept a secret at all times and a local copy could be found with the current web development head of the club.

## Adding news articles
You can directly add news articles to the website by using the Postman collection, usually available with the current web development head of the club. You'll also need an API key so that your requests are validated by the app. 
 