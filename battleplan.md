feat 1: done

feat 2: done

feat 3:

    .As a reader I want to search articles, so I can find something I am interested in

    .The search article page displays a list of articles

    .Entering a searchterms filters the articles

    .We want to display the articles if the searchterm matches something inside the title, catergoryId or author

    x load all articles into the page
    x make a text input
    x make it controlled with state
    x depending on the state, the rendered list of articles changes
    x filters on title, category or author

done!

feat 4:
. As a customer I want to read an article and leave comments, so I can feel involved.
. There is an Article details page which displays a specific article
. The comments for the article are also displayed
. There is a form to leave your own comment

Criteria Points
x A the specific article is displayed with a title, author, image and content 1

x A list of comments is displayed for the article, with name and comment 1

x Id of the article the user wants to see is dynamic and determined using a route parameter 1

x The data is fetched from the api, not hardcoded 1

x There is a form on the page with inputs for name and comment and a button to submit 0.5

x The state of the form is controlled using React useState hook(s) 0.5

x When the form is submitted, a new comment is displayed on the page 2

x The comment is displayed at the top of the list of comments 1

x The comment form is seperate component and uses a callback prop to change the state of the parent component 3

-Submitting the form refreshes the page -2
-There is a warning in the console regarding "key" props -1
Total 11

FEAT 5:
As a customer I want to view articles from a specific category, so I can explore a topic further
The category page displays articles with a specific categoryId
The category displayed depends on which link a user has clicked
GET /categories/:categorId/articles

https://my-json-server.typicode.com/Codaisseur/articles-comments-data/categories/devops/articles

x The categoryId the user wants to see is displayed on the page 1
x The category of the list of articles the user wants to see is dynamic and determined using a route parameter 1
x A list of articles with that categoryId is displayed, each with a title, author, image and categoryId 1
x A component is reused to display the articles 1
x There is a warning in the console regarding "key" props -1
