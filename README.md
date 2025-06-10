## In this note book, objective is to prepare a company brouchure using LLM.
## 1. we use http request to scrap the website data.
## 2. we use beautiful soup to parse the html content to derive, text, emailid, links in any of company website.
## 3. we call mini LLM and provide the links and will ask LLM if any of the links are useful in creating the brouchure.we provide multi-shot prompting to provide more information
## 4. we call another LLM with the text and releavant links to prepare a brouchure for the sales team. 
## 5. we call another LLM to convert the brochure from english to spanish.
## 6. We are calling another LLM to evaluate the effeciency of text conversion from the previous LLM. This is a sample version of Agentic AI solution.
