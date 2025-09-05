<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Smart Cabin pricing

Final project for the Building AI course

## Summary

This project uses machine learning to predict cabin prices based on features such as size, sauna, distance to water, number of bathrooms, and proximity of neighbors. It demonstrates data preprocessing, model training, and evaluation with clear reproducible code. 


## Background

People looking to buy or sell cabins often struggle to estimate a fair market price.
Real estate pricing can be inconsistent due to subjective valuation and lack of transparent data-driven tools.
Over- or underpricing leads to financial losses and slower sales.
Automated price prediction makes the process faster and more objective.
Personal motivation: I enjoy applying machine learning to practical problems. Cabin pricing is a relatable example where data-driven predictions can make a real difference.
Importance: Accurate, explainable AI for property valuation can benefit both buyers and sellers, reduce uncertainty, and demonstrate how machine learning models can be used for decision support in everyday life.

## How is it used?

Collect cabin data (size, sauna, distance to water, bathrooms, neighbors).
Train the machine learning model with the provided scripts or notebooks.
Save the trained model for reuse.
Run the prediction script with new input values to estimate the cabin price.
Optionally, extend the project with more features or connect it to a simple web app for interactive use.

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](images.jpeg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
