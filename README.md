![Header](week-4/Assets/image/header%20cut.png)

<h1 align="left">Welcome petrolhead ! <img src="https://raw.githubusercontent.com/muhammad-avicena/profile/master/wave.gif" width="30px" height="30px" /> </h1>
Konnichiwa minna-san, I'm Rizqi Akbar. I'm presenting my beautifully masterpiece from NISSAN that exudes wildness and dominance. From a legendary hand with precision. To be focus on customer satisfaction, a bulletproof engine, perfect stability, this car offers a power of engine mass production with high standard of quality and style. You must be like it !

## STRUCTURE 📰

- Header
  - Dark mode
  - Navbar
- Main
  - Photo AI
  - R34 information
  - The whistle of domination
- Footer
  - Form

## INGREDIENTS I USE 📜

- HTML
- CSS
- Internal Source
  - Icon
  - Image

## HOW TO SET UP 📰

You will need a github account to clone this repository, make sure you're connected to github.

1. Clone this repository

```
git clone https://github.com/revou-fsse-3/module-2-LOOL18.git
```

2. Create a new branch named "develop", in this repository we would like to develop the website with personal information.

```
git branch -b "develop"
```

3. Once it's created, checkout to a new branch

```
git checkout -b "develop"
```

4. Develop & modify the website with your personal information, once it's done you will need to push it.

```
git add .
git commit -m "update message" // make sure to give details commit message to get better logs
git push origin develop
```

5. Once you're done, you can merge into main/master branch for production build.

```
git checkout main
git pull origin main // pull the latest version before commit merge
git merge develop // if there are any conflicts, you should resolve them manually
git commit -m "Merge develop into main"
git push origin main
```

## DEPLOYMENT ⚙️

The project has been successfully deployed using Netlify. You can access the production version of the website by following this link: [https://www.dartvader.cloud/](https://www.dartvader.cloud/) or [this link](https://www.dartvader.cloud/).

### Deployment status :

[![Netlify Status](https://api.netlify.com/api/v1/badges/a9be8e5e-574a-4a65-9886-9920c468567e/deploy-status)](https://app.netlify.com/sites/prismatic-seahorse-8a8d12/deploys)

---

## **1. Connect your account to Netlify !**

he first step to deploy in Netlify is creating a new account or use existing account. As a beginner progammer, I would prefer using GitHub account instead.

After you successfully login, you will be redirected to dashboard of Netlify app. In this scenario, you will need to import your existing project from github to netlify. Add new site -> Import existing project -> Connect via GitHub.

## **2. Auto Deploy with Netlify !**

One of the benefit using your GitHub account connected to Netlify is that you don't have to worry about re-deploying your project manually, once there are changes that have been pushed in your repository, it will automatically re-deployed by Netlify within second.

## **3. Domain Registrar with NiagaHoster & Cloudfire !**

Go to [https://niagahoster.co.id](https://niagahoster.co.id) and log in or create a new account. Check available domain that you wanted and make it yours.

After that, go to [https://dash.cloudflare.com/](https://dash.cloudflare.com/) and log in or create a new account. You will be redirected to dashboard, add the domain that you have bought previously.

## **4. Modify your project with favorite customize domain !**

You're on the final step to bringing live your project with custom domain. Go to dashboard Cloudfire -> DNS Records -> CloudFire NameServer. You will see the information of Nameserver that is given to you.

Copy these nameserver and jump into dashboard overview of NiagaHoster. You should replace it with NameServer of CloudFire. After that, go to Netlify Dashboard -> open your project -> Custom domain -> Add domain that you have set previously. In thise case, you will see they're awaiting for external DNS. You will get some information such as IPv4 and domain name that you should input it to CloudFire.

Final step, go to Dashboard Cloudfire -> DNS Records -> Add record domain -> set them accordingly.

## **5. Congratulations, You're done !**

_You should wait within 1x24 hours to let the NiagaHoster and Cloudfire setting up the DNS, it could be faster or slower depending on the provider internet that you're using.
Feel free to explore the website and try out the different features. I appreciate any feedback and suggestions to further improve the user experience.
Happy browsing!_
