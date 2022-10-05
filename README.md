# Your-ORM-E-Commerce-Back-End


## USER STORY


AS A manager at an internet retail company,

I WANT a back end for my e-commerce website that uses the latest technologies,

SO THAT my company can compete with other e-commerce companies.


## ACCEPTANCE CRITERIA

GIVEN a functional Express.js API,

WHEN I add my database name, MySQL username, and MySQL password to an environment variable file,

THEN I am able to connect to a database using Sequelize.

WHEN I enter schema and seed commands,

THEN a development database is created and is seeded with test data.

WHEN I enter the command to invoke the application,

THEN my server is started and the Sequelize models are synced to the MySQL database.

WHEN I open API GET routes in Insomnia for categories, products, or tags,

THEN the data for each of these routes is displayed in a formatted JSON.

WHEN I test API POST, PUT, and DELETE routes in Insomnia,

THEN I am able to successfully create, update, and delete data in my database.



## WALKTHROUGH - EXAMPLES

The image below is an example of the schema clearing any existing database and then creating ecommerce_db database.

![0 - schema](https://user-images.githubusercontent.com/107973681/193961076-3de10534-0594-4ad8-9618-8d31ddc06397.png)


The image below is an example of the npm i being ran to install node packages and show them being synced to MySql live bases.

![1 - database synced](https://user-images.githubusercontent.com/107973681/193961808-3fbfdaa7-01e2-460f-b9c8-8885f33d1c5d.png)


The image below is an example of substantiating the seeds running "npm run seed" that creates the databases

![1 - seeds synced](https://user-images.githubusercontent.com/107973681/193962084-5edc79a0-ae04-44e8-b2dc-720bf27ad95b.png)


The image below is an example of the Product object being initialized.

![2 - product init](https://user-images.githubusercontent.com/107973681/193962142-3a058195-1184-4154-85d1-bf4838102179.png)


The image below is an example of the findAll function initializing the attributes for "Product".

![3 - product findAll](https://user-images.githubusercontent.com/107973681/193962210-65678c6c-c07c-4172-b7b2-da78bcf8d5ac.png)


The image below is an example of access to the database through Insomnia, displaying the local server. Then api GET Tag by ID and the data shown within the preview.

![4 - api, get](https://user-images.githubusercontent.com/107973681/193962350-76db12fc-be5a-495e-83c4-7752630dfb88.png)


The image below is an example of access to the database through Insomnia, displaying the api GET Tag by ID and the data shown within the preview.

![4 - api GET Tag by ID](https://user-images.githubusercontent.com/107973681/193962779-8146ca92-c374-41ca-92de-c65d0d6dacf4.png)


The image below is an example of access to the database through Insomnia, displaying the api CREATE and the data including "tag_name". 
Then the preview shows the id:9 and the "tag_name".

![4 - api create](https://user-images.githubusercontent.com/107973681/193962968-6fefa8e1-fb33-460b-a154-11b470b72c68.png)



## LINKS


GitHub: https://github.com/SalmanDanesh93/Your-ORM-E-Commerce-Back-End

Video Walk-Through: https://drive.google.com/file/d/1cC_MdHkSK6omHV7yzqN6gHOljxvducvH/view
