# 0x09. Implement a design from scratch
## Details
 By: Nicolas Philippot, UI/UX designer and Guillaume Salva, CTO at Holberton School Weight: 3Project will startAug 11, 2022 12:00 AM, must end byAug 16, 2022 12:00 AMManual QA review must be done(request it when you are done with the project)### Concepts
For this project, we expect you to look at this concept:
* [Implement a design](https://intranet.hbtn.io/concepts/220) 

In this project, you will implement from scratch, without any library, a web page. You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously. 
You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have a fully functional web page that looks the same as the designer file.
Here the final result:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/60df485eb772ecbad54a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220811%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220811T213257Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b950b37f2e6dd04668c0cf9aa2a6e5938bc185f2f6e0e3f76ad514d618318c18) 

This webpage has been designed by Nicolas Philippot, UI/UX designer.You can find final screens  [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/622/Archive.zip) 

### Requirements
* you are not allowed to import external CSS framework (like Bootstrap)
* you are not to use Javascript
## Tasks
### 0. Read and be familiar with Figma
          mandatory         Progress vs Score  Task Body Create an account in  [Figma](https://intranet.hbtn.io/rltoken/eumOUW-eMS4X9ZDZg9KPLg) 
  and open this  [project](https://intranet.hbtn.io/rltoken/2ED3P1a2wnbQqRLi8aXJKw) 
  and “Duplicate to your Drafts” to have access to all design details.
If you can’t access to it, please find here the  [Figma file](https://intranet.hbtn.io/rltoken/NxsDNicWs5KSlsR94kt52A) 

 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220811%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220811T213257Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=15c43b068e8168f1fe5579e0676dab8a217c49b45ab308c990387bed91afe8cb) 

Important notes with Figma:
* if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](https://intranet.hbtn.io/rltoken/wltHny-KZP3B8JFRvpmVjA) 
 and [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/Qb96K4nTPQJO1paP_OBELw) 

* some values are in float - feel free to round them
For this task, please write an amazing   ` README.md ` 
Interactions note:
* the web page must switch to the mobile version when the screen width is 480px or less
* links hover/active:  ` #FF6565 ` 
* button hover/active:  ` opacity: 0.9 ` 
* max width of the content: 1000px centered in the page
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` README.md ` 
 Self-paced manual review  Panel footer - Controls 
### 1. Header
          mandatory         Progress vs Score  Task Body Building a web page the right way, is not easy - expect if you put in place strong foundations:
* reset CSS styling
* use variables
* simple/“as generic as you can” CSS selectors
* avoid using super specific CSS selectors as much as possible
* simple HTML structure -  ` div `  containers are your friend!
Last advice: Personally, I always start to build a web page from outside to inside and from top to bottom. But you can try to other way - it’s fine - but you should structure the way that you will implement a component and not get lost with HTML tags.
Now, your turn!
For this first task:  create the header/hero piece
Here an archive of all assets needed:  [images_0x09.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/d1597894d79386c83b9b.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220811%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220811T213258Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=fb01bf80c38e2336253c18e30e516997b8d5e8391180616e57f934c69ed76e02) 

Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/4a93441c93989ad7ea72.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220811%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220811T213258Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=68556195b22ea9659f444a4bfae0f31a0429fec08754017a8b71f5ab343e69fd) 

Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/75a582f98640445a2dbf.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220811%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220811T213258Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=221b1ecbbc21788dec2a142116485269d4c4801a061303d053865bf70866d1c0) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 0-index.html, 0-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 2. "What we do..." section
          mandatory         Progress vs Score  Task Body Copy files from the previous task.
For this second task:  create the “What we do…” section
In this section, you will need custom font icons. Here the archive of it:  [holberton_school-icon.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220811%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220811T213258Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=65a35365020403e1e76790a917874d5c88f5c7dc53cf2dc7c9de32c6dd711fdd) 
  Inside you will find demo page of how to use it.
Important:  try to build as generic as you can… you will probably need some components in next section.
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 1-index.html, 1-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 3. "Our results" section
          mandatory         Progress vs Score  Task Body Copy files from the previous task.
For this third task:  create the “Our results” section
Now you can reuse components form the previous task!
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 2-index.html, 2-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 4. Contact us
          mandatory         Progress vs Score  Task Body Copy files from the previous task.
A good landing page has always a contact form.
You are free to add any animations and/or constraints on fields.
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 3-index.html, 3-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 5. Footer
          mandatory         Progress vs Score  Task Body Copy files from the previous task.
Last piece of the page… the Footer!
When you are done, here the result:
Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3b5a9f7948a58d58bd43.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220811%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220811T213258Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=aa59638bcd72ef8d6d459dba9e19ff008cbacc9c151489d43e434fad2906b1c4) 

Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/83d6311e87d4775ca4b3.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220811%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220811T213258Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=28fb448a52018584947585dd92c31cf0d1082ae11aabe3427708069893157dcc) 

And you are done! 
Good job!
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 4-index.html, 4-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 6. Replace background image with... code!
          #advanced         Progress vs Score  Task Body In the section “Our results”; without the use of an image file, draw each pentagon using HTML and CSS.
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 100-index.html, 100-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 7. Let's animate items
          #advanced         Progress vs Score  Task Body From   ` 4-index.html `   and   ` 4-styles.css `  , add fun animations to “What we do…” and “Our results” sections items row. Either all the time, either when hover.
Scaling, opacity, rotation, bouncing… many options!
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 101-index.html, 101-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 8. And SASS??
          #advanced         Progress vs Score  Task Body Take your   ` 101-styles.css `   file and create a   ` 102-styles.scss `   that will be the SASS version of it.
 ` $ sass 102-styles.scss > 101-styles.css
 `  Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 102-styles.scss ` 
 Self-paced manual review  Panel footer - Controls 
Ready for a  manual review