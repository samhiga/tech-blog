# tech-blog

## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| Git | [https://git-scm.com/](https://git-scm.com/)     | 
| Node.js | [https://nodejs.org/api/cli.html](https://nodejs.org/api/cli.html)   |
| MySQL | [https://www.mysql.com/](https://www.mysql.com/)   |
| NPM | [https://www.npmjs.com/](https://www.npmjs.com/)   |
| mysql2 | [https://www.npmjs.com/package/mysql2](https://www.npmjs.com/package/mysql2)   |
| dotenv | [https://www.npmjs.com/package/dotenv?activeTab=readme](https://www.npmjs.com/package/dotenv?activeTab=readme)   |
| Sequelize | [https://sequelize.org/](https://sequelize.org/)   |
| Heroku | [https://insomnia.rest/download](https://insomnia.rest/download)   |
| Express | [https://expressjs.com/](https://expressjs.com/)   |


## Description 

 Walkthrough Video []

This web page allows users to create profiles to post tech-related blogs and comment on others as well. They can create profiles.




## Table of Contents 

* [Javascript Example](#javascript-example)
* [Usage](#usage)
* [Learning Points](#learning-points)
* [Author Info](#author-info)



## Javascript Example

To get a hold of this project, simply navigate to my Github profile and select the repo "tech-blog". From there copy the SSH link into your terminal, Gitbash, or whatever application you prefer and use git copy and then paste the link. You can then open it using VS Code and view it through the deployed link.


```javascript
   if (name && password) {
      const response = await fetch('/api/users', {
        method: 'POST',
        body: JSON.stringify({ name, email, password }),
        headers: { 'Content-Type': 'application/json' },
      });
  
      if (response.ok) {
        document.location.replace('/dashboard');
      } else {
        alert(response.statusText);
      }
    }
  };
```

In the above code, I created a form handler so users would be able to sign up and create a profile.



## Usage 
To use this site, create a profiled and by adding a username and password. You can then create a blog post using the create blog post button and add a title and content. You can also comment on other blog posts to share your thoughts on the subject.



## Author Info


### Sam Higa 


* [Portfolio](https://samhiga.github.io/my-portfolio/)
* [LinkedIn](https://www.linkedin.com/in/sam-higa-b887b9209/)
* [Github](https://github.com/samhiga)