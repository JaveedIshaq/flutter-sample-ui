# Flutter Sample UI/UX Examples  🍟 

Flutter Sample UI Layouts
<img src="https://user-images.githubusercontent.com/48018942/111353594-75464080-86ab-11eb-9379-ab07031c1e54.png" height="250" width="450" />

[![Repo](https://img.shields.io/badge/-Awesome-181717?style=flat-square&logo=github)](https://github.com/JaveedIshaq/flutter-sample-ui) [![Flutter](https://img.shields.io/badge/-Flutter-46d1fd?style=flat-square&logo=flutter)](https://flutter.dev/) [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/JaveedIshaq/flutter-sample-ui&count_bg=%231182C2&title_bg=%23585858&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)



Looking for an awesome UI kit for Flutter? 
Here is a curated list of a few awesome Flutter UI design templates to integrate in your Flutter app and save your time on designing widgets. You can check more UI design templates here.


**Show some ❤️ and star ⭐ the repo to support the project**

## Index 📝 

 1. [Google Products App UI](https://github.com/JaveedIshaq/google-products-app)
 2. [Flutter Courses App UI](https://github.com/JaveedIshaq/flutter-courses-app-ui)
 3. [Food Delivery app UI](https://github.com/JaveedIshaq/food-delivery-app-ui)
 4. [Flutter Login App UI](hhttps://github.com/JaveedIshaq/baking_lessons_login_ui)
 5. [Lottery App UI](https://github.com/JaveedIshaq/flutter_lottery_app_ui)
 6. [Chat Ui](https://github.com/JaveedIshaq/flutter-sample-chat-ui)
 7. [Flutter Login Sign Up UI](https://github.com/JaveedIshaq/flutter_ui_samples/tree/master/login_signup_ui)


</br>


### 1.  Google Products App UI  🍦 


<a href="https://github.com/JaveedIshaq/google-products-app"><img src="https://github.com/JaveedIshaq/google-products-app/raw/master/screenshot-2021-08-16_21.31.37.229.png?raw=true" heigth="400" width="250"/></a>

---

### 2. Flutter Courses App UI 🍨 

</br>

<a href="https://github.com/JaveedIshaq/flutter-courses-app-ui"><img src="https://github.com/JaveedIshaq/flutter-courses-app-ui/raw/master/FLutter_Courses_App_UI_screenshot.png?raw=true" heigth="400"/></a>


---

### 3. Food Delivery app UI  🎂 


<a href="https://github.com/JaveedIshaq/food-delivery-app-ui"><img src="https://github.com/JaveedIshaq/food-delivery-app-ui/raw/master/food-delivery-app-ui-flutter.png?raw=true" heigth="400"/></a>

</br>

---

### 4. Flutter Login App UI  🍨 

</br>

<a href="https://github.com/JaveedIshaq/baking_lessons_login_ui"><img src="https://github.com/JaveedIshaq/baking_lessons_login_ui/raw/master/flutter-casa-Login-UI.png?raw=true" heigth="400"/></a>

**Packages in use:**
1. [flutter_svg](https://pub.dev/packages/flutter_svg)
2. [flutter_staggered_grid_view](https://pub.dev/packages/flutter_staggered_grid_view)

**Fonts**
1. [Poppins](https://fonts.google.com/specimen/Nunito)
---
### 5. Lottery App UI  🍧 

<a href="https://github.com/JaveedIshaq/flutter_lottery_app_ui"><img src="https://github.com/JaveedIshaq/flutter_test_app/raw/master/screenshot/2-home.png?raw=true" heigth="400" width="250"/></a>
---


### 6. Chat UI 🎂 

A Flutter Sample Chat UI View


<a href="https://github.com/JaveedIshaq/flutter-sample-chat-ui"><img src="https://raw.githubusercontent.com/JaveedIshaq/flutter-sample-chat-ui/master/chatui-screenshot.png" heigth="400" width="250"/></a>


</br>

### 7. Flutter Login Sign Up  UI 🎂 

A Flutter Sample Chat UI View


<a href="https://github.com/JaveedIshaq/flutter_ui_samples/tree/master/login_signup_ui"><img src="https://github.com/JaveedIshaq/flutter_ui_samples/raw/master/login_signup_ui/screenshots/welcome_screen.jpg" heigth="400" width="250"/></a>


</br>

# Widgets :rocket:

List of well-designed widgets that you will actually need and find useful rather than overwhelming you with a plethora of low-quality ones.

## Index 📝 

 1. [Rounded input field](https://github.com/Chromicle/awesome-flutter-ui/blob/master/widgets/rounded_input_field.dart)
 2. [Flushbar alert service](https://github.com/Chromicle/awesome-flutter-ui/blob/master/widgets/alert_service.dart)
 
</br>

### 1.  Rounded Input field 🍦 
**GIF** \
<img src="https://user-images.githubusercontent.com/48018942/95119656-ec28f600-0769-11eb-8d29-d5d3e54a7aac.gif" height="250" width="450" />


**Use**
```dart
RoundedInputField(
    textEditingController: controllerName,
    hintText: "Your Email",
    icon: Icons.email,
    cursorColor: Colors.black,
    editTextBackgroundColor: Colors.grey[200],
    iconColor: Colors.black,
    onChanged: (value) {
      name = value;
     },
 )
 ```
---

### 2. Flushbar alert service 

To use this widget you have to include one denpendency called [flushbar](https://pub.dev/packages/flushbar) in your `pubspec.yaml`, if you want error alert you have to give `AlertType.error` in type feild same applies to warning \
**GIF** \
<img src="https://user-images.githubusercontent.com/48018942/95247709-d54ed600-0833-11eb-92ab-42615c09a352.gif" height="150" width="500" />

**Use**
```dart
CustomButton(
    text: "Add to Cart",
    onPressed: () {
      AlertService().showAlert(
         context: context,
         message: 'product has been added to cart',
         type: AlertType.success,
         );
     },
 )
```


### Author ✍️
1. [![Javeed Ishaq](https://avatars.githubusercontent.com/u/9929619?v=3&s=32) @javeedishaq ](https://github.com/javeedishaq) 


### Looking to contribute? :computer:
Please read [CONTRIBUTING.md][contributor-guide] before writing a pull request. Any and all help we can get is welcome :)

### License :memo:
This repository is licensed under MIT License. Find [LICENSE][license] to know more.

### Note

These examples are open to all kinds of contribution in all of its categories. **dude, they are completely free**😜 \
If you found this project useful, then please consider giving it a :star: on Github and sharing it with your friends via social media⚡. \
Happy Coding 💻.

[contributor-guide]: CONTRIBUTING.md
[license]: LICENSE# New Document
