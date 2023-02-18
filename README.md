# FBI (Facts 'Bout Ingredients)
What's sodium benzoate? Do you ever ask yourself what chemicals companies are putting in your food?
FBI will uncover all the ingredients for you!

## Tech
- Uses optical character recognition to scan ingredient labels for the list of ingredients
- Utilizes SerpApi to search google for information about the ingredients
- Built using React and Flask
## Gallery
**Landing Page:**

![image](https://user-images.githubusercontent.com/74084786/219827722-4540ce18-c456-4a02-bb7d-8bbb97a1b092.png)

**Ingredients in bud light beer:**

![image](https://user-images.githubusercontent.com/74084786/219827740-2fd6bb3f-75a6-4c3b-8ecd-9d1e0313b136.png)

**How to set up:**

Back-end:
1. cd into /api
2. pip install -r requirements.txt
3. flask run

Front-end (in a seperate terminal):
1. cd into /client
2. npm install
3. npm start

Using the google search api:
1. pip install google-search-results

Using PaddleOCR
1. pip install paddlepaddle
2. pip install "paddleocr>=2.0.1"
