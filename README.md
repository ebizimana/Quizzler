# Quizzler
Is an app that helps you question people in your field, friends, or coworkers.... in nice stylic way and simple to use ever. 

## Finished App
![Finished App](https://github.com/londonappbrewery/Images/blob/master/Quizzler.gif)

## Lesson Learned
- How to make class 
- What clases and objects are and their diferences and functionality
- Learned Model Visual Controle (MVS) model which is very important 
- To make an aray that containes a class in it 
- How to make a Alert pop up
- Learned how touse third party projects ("No need to reinvert the wheel")

## How to make an array that contains a class
- First make a class e.g PartsOfACar class 
- second declare which parts of the car may be different e.g var door, var paint, var tires, var model
- third if you make an array of the class e.g var car[PartsOfACar]()
- by doing that, each index will contain all this different features and you can make as many as index as you want. e.g car[0].paint can be set to whatever you ant as you leave other parts not touched 

## How to make an alert pop up
- first declare UIAlertController() funcction e.g let alert = UIAlertController()
- Declare UIAlertAction() Function e.g let restart = UIAlertAction()
- use AddAction e.g alert.AddAction(restart)
- Finally use present function e.g present(alert,true,nil)



Copyright 2015 London App Brewery
