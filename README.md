# Esilv_Api_Project

### Project
**Create an API for AI News Overview**

This project involves creating an API that provides news related to Artificial Intelligence (AI). Each group will select an AI-related site (e.g., OpenAI blog) as their source.

### Objective

The goal is to fetch information from the chosen site, either by scraping or through an existing API. You will create several endpoints for different purposes:

    - /get_data: Fetches a list of articles from the site. Retrieving 5 articles might be sufficient.
    - /articles: Displays information about the articles, including the article number, title, publication date, etc., but not the content itself.
    - /article/<number>: Accesses the content of a specified article.
    - /ml or /ml/<number>: Executes a machine learning script. Depending on the desired goal, it applies to either all articles or a single one. For example, sentiment analysis.

You can choose website about many subject like:

    - Updates on new AI tools.
    - News about image generation.
    - Information on new models.
    - Research papers, such as those from ArXiv or Google DeepMind.

### Process

    1. Each group should create a branch named after the names of the group members.
    2. Inside the branch, create a working directory named after the chosen site.
    3. Add a file named composition.txt that lists the members of the group.
    4. Add a section below these rules to explain your project, describe the created endpoints and their uses, and provide examples.
M e m b e r   :   R � m i  
 T h i s   A P I   p r o v i d e s   n e w s   r e l a t e d   t o   A r t i f i c i a l   I n t e l l i g e n c e   ( A I )   f r o m   A r X i v   s i t e   b y   f e t c h i n g   a r t i c l e s   f r o m   i t s   A P I . 
 
   # # # O b j e c t i v e s   : 
   
   - F e t c h e s   a   l i s t   o f   a r t i c l e s   f r o m   t h e   A r X i v   A P I . 
   - D i s p l a y s   i n f o r m a t i o n   a b o u t   e a c h   a r t i c l e s   ( i d , t i t l e , p u b l i s h e d   d a t e , l i n k . . . )   w i t h o u t   i t s   c o n t e n t 
   - A c c e s s e s   t h e   c o n t e n t   o f   a   s p e c i f i e d   a r t i c l e . 
   - E x e c u t e s   a   M a c h i n e   L e a r n i n g   s c r i p t 
 
   # # # H o w   t h e   c o d e   i s   o r g a n i s e d : 
 
   - I n s t a l l a t i o n   o f   P a c k a g e s 
   - I m p o r t a t i o n   o f   r e q u i r e d   l i b r a r i e s   ( f l a c k   f o r   t h e   c r e a t i o n   o f   o u r   A P I ) 
   - I n i t i a l i s a t i o n   o f   o u r   A P I 
   - I m p l e m e n t a t i o n   o f   o u r   d i f f e r e n t s   e n d p o i n t s   ( / g e t _ d a t a , / a r t i c l e s , / a r t i c l e / < i d > , / m l )    
 