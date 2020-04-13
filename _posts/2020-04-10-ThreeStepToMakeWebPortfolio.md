![portfolio.jpg](/img/portfolio.jpg)


Hello folks I am back with my new article on how to make a cool portfolio. In this article I will explain all of the steps starting from the creating your portfolio to host it on your personal domain. Sounds interesting ? Yeah !! Let's do it...

## **STEP 1: Creating your static HTML portfolio project**

The first step is to create the basic html static web-page, those who are expert in html can easily create it and add some cool css stuff in it.

But I do care about the others who are not handy with html, so you guys can just hit the google to check for some free html portfolio samples and then download it. Next you can open the sample project in any of your favourite editor.

At this stage your are ready to make changes in the sample and paste your own content like your intro, your works, your blogs, etc.  **This can look something like this-**

![No alt text provided for this image](https://media-exp1.licdn.com/dms/image/C5112AQFRM1fsmLywOg/article-inline_image-shrink_1000_1488/0?e=1592438400&v=beta&t=X3EgiuuWac4bovoKmipbKKfIX3q6DfCTqdITq1ThHrw)

Since I love android studio so I have used it for editing the project, on the left are my static pages like about-me, index, blogs, services, etc. And in the right you can see how I am making changes to those pages. When you want to review the changes made by you just open the page in any browser and boom..

You can also use Jekyll Theme([Link](https://jekyllthemes.io/free)), these themes are very easy to use and best part is you can easily host it on GitHub.

## **STEP 2:** **Hosting your static web portfolio**

Till now you are ready with your cool portfolio now all you need to do is to host it somewhere so that everyone can easily access it.

There are hundred of ways to host your website but I will tell you some of the cool and easy to use and of-course free of cost. You can use amazon AWS, google cloud platform, word-press, etc. But for this propose I would recommend you to use the GitHub Pages ([Link](https://pages.github.com/)). GitHub pages is very easy to use all you need to do is to create the name of your repository like  **username+.github.io** and push your project to this repository.

After you push your project to GitHub repository successfully it is hosted now you can use the public link to see your portfolio anywhere the link will be something like  **(https://+username+.github.io)**  for example  [https://yadav-shivam.github.io/](https://yadav-shivam.github.io/)

It can look something like this-

[![No alt text provided for this image](https://media-exp1.licdn.com/dms/image/C5112AQFMqtboR9EBmw/article-inline_image-shrink_1000_1488/0?e=1592438400&v=beta&t=jP_SNIKN3AsTS2pkQ8GlEnmz8yM1-NW3CMShU26BmjE)](http://github.com/yadav-shivam/yadav-shivam.github.io)



## **STEP 3: Adding your custom domain to your portfolio**

This is the final step and of-course a very important step if you want to use your own domain to access your portfolio.

Since the GitHub pages support custom domain feature so it's not going to be a big trouble for you.

First of all you need to buy a custom domain of your name from GoDaddy([Link](https://in.godaddy.com/)), after that there are two key steps to do it.

### A) Set domain in GitHub project

![No alt text provided for this image](https://media-exp1.licdn.com/dms/image/C5112AQHiO8Eq2L_QZw/article-inline_image-shrink_1000_1488/0?e=1592438400&v=beta&t=mdwtN1gfokUJge-KPb59CJFveX8hAkMRRbBR7tkuydI)

Open  **settings**  page in your GitHub repository and fill the custom domain which you purchased from GoDaddy.

**Note:**  Setting “custom domain” creates a file named **CNAME** in the same repository. Don’t delete it.

### B) Set custom resource record for domain

This step is specific to your domain name register (like GoDaddy, Domain.com, Google Domains, etc). All you need to do is set A & CNAME records for the selected domain.

[![GIF is taken from GoDaddy website.](https://media-exp1.licdn.com/dms/image/C5112AQFxRd4DVshnTw/article-inline_image-shrink_1000_1488/0?e=1592438400&v=beta&t=x36-ziLGrLj_uA3Z7-L0k8GV8F2PgJYzm1bsxEoS2UM)](http://in.godaddy.com/help/add-a-cname-record-19236)

For A record, set 185.199.108.153, 185.199.109.153, 185.199.110.153 and 185.199.111.153. To redirect www subdomain to the original domain, add a CNAME record with your GitHub pages profile URL with a .(dot) in the end, for example, ‘_YOUR-GITHUB-USERNAME.github.io._’.

**_Official References:_** _For most up to date IP Addresses, use GitHub’s_ [_official documentation_](https://help.github.com/articles/setting-up-an-apex-domain/) _and for setting up CNAME use this_ [_documentation_](https://help.github.com/articles/setting-up-a-www-subdomain/)_._

That’s it, both www.your-domain.com and your-domain.com will now go to your selected GitHub pages site _(may need to wait up to 24 hours)_. If you want to see a live example, you may visit my portfolio “[shivamyadav.live](https://shivamyadav.live/)” hosted via GitHub [pages](https://github.com/yadav-shivam/yadav-shivam.github.io) repository ✌️.

_Congratulations you are done with creating your beautiful portfolio... Do post your comments or get in touch with me if you need any help._