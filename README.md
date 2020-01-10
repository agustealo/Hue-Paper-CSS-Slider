![Paper Logo](https://raw.githubusercontent.com/agustealo/paper-project-assets/master/images/PaperHueSlider/Paper-Slider-Logo.png?raw=true)

# Hue Paper CSS Slider
Hue Paper CSS slider, I'm a lightweight, no-frills slider. Built by [Agustealo](https://agustealo.com "Agustealo") with :heart: using pure CSS, HTML and no third party dependencies.
Love Hue Paper CSS Slider but rather JavaScript?! Check out the JavaScript version [Hue Paper Slider](https://github.com/agustealo/Hue-Paper-Slider "Hue Paper Slider")

## Without text
![Hue Slider Screenshot](https://raw.githubusercontent.com/agustealo/paper-project-assets/master/images/PaperHueSlider/screenshot-withOutText.jpg?raw=true)

## Setup

1. Lets start by adding our CSS to the page header. Here is the typical method or whatever is best for your project ```<link rel="stylesheet" href="hue-paper-css-slider.css" /> ``` 

2. Copy and place all the Paper Hue CSS Slider's HTML chunk into your html body.

   ```html
   
    <div class="hue-slide">
      ...
      <!-- everything goes here-->   
      ... 
    </div>
   
   ```

3. Now edit the HTML to add slids with your own images to the slider.

   ```html
        ...

        <!-- Edit the following with your own images-->
        
        <!-- Slides-->
        <ul class="hue-slide_items">
          <li class="hue-slide_item">
            <img src="https://raw.githubusercontent.com/agustealo/paper-project-assets/master/images/graphics/hue-slider-img-1.jpg"/>
          </li>
          <li class="hue-slide_item">
            <img src="https://raw.githubusercontent.com/agustealo/paper-project-assets/master/images/graphics/hue-slider-img-2.jpg"/>
          </li>
          <li class="hue-slide_item">
            <img src="https://raw.githubusercontent.com/agustealo/paper-project-assets/master/images/graphics/hue-slider-img-3.jpg"/>
          </li>
          <li class="hue-slide_item">
            <img src="https://raw.githubusercontent.com/agustealo/paper-project-assets/master/images/graphics/hue-slider-img-4.jpg"/>
          </li>
        </ul>

        ...
   ```


## With Text
![Hue Slider Screenshot](https://raw.githubusercontent.com/agustealo/paper-project-assets/master/images/PaperHueSlider/screenshot-withText.jpg?raw=true)

## Setup

1. Lets start by adding our CSS to the page header. Here is the typical method or whatever is best for your project ```<link rel="stylesheet" href="hue-paper-css-slider.css" /> ``` 

2.  Copy and place all the Paper Hue CSS Slider's HTML chunk into your html body.

   ```html
   
    <div class="hue-slide">
      ...
      <!-- everything goes here-->   
      ... 
    </div>
   
   ```

3. Now edit the HTML to add slides with your own images with Title Header and text copy to the slider.

   ```html
        ...

        <!-- Edit the following with your own images and content-->
        
        <!-- Slides-->
        <ul class="hue-slide_items">
          <li class="hue-slide_item">
            <img src="https://raw.githubusercontent.com/agustealo/paper-project-assets/master/images/graphics/hue-slider-img-1.jpg"/>
            <div class="hue_content"><div>
              <header class="entry-header">
                <h1 class="entry-title">Hue Slider</h1>
              </header>
              <p>
                Hue Paper CSS Slider, this page is to demonstrate my Awesome features.
                </p><ul>
                  <li>I am lightweight</li>
                  <li>Independant of third party bloats</li>
                  <li>Easy to setup and use</li>
                </ul>
              <p></p>
              <input class="hue-button" onclick="window.location.href = '#hue-container'" type="button" value="Read More">
            </div></div>
          </li>
          <li class="hue-slide_item">
            <img src="https://raw.githubusercontent.com/agustealo/paper-project-assets/master/images/graphics/hue-slider-img-2.jpg"/>
            <div class="hue_content"><div>
              <header class="entry-header">
                <h1 class="entry-title">Easy Setup</h1>
              </header>
              <p>
                Easy to setup and get up and running in no time.
                Just add the CSS and your content to the HTML markup.
              </p>
              <input class="hue-button" onclick="window.location.href = '#hue-setup'" type="button" value="Read More">
            </div></div>
          </li>
          <li class="hue-slide_item">
            <img src="https://raw.githubusercontent.com/agustealo/paper-project-assets/master/images/graphics/hue-slider-img-3.jpg"/>
             <div class="hue_content"><div>
                <header class="entry-header">
                  <h1 class="entry-title">I am Hue</h1>
                </header>
                <p>
                  Ut enim ad minim veniam, quis nostrud exercitation ullamco
                  laboris nisi ut aliquip ex ea commodo consequat.
                </p>
                <input class="hue-button" onclick="window.location.href = '#'" type="button" value="Read More">
              </div></div>
          </li>
          <li class="hue-slide_item">
            <img src="https://raw.githubusercontent.com/agustealo/paper-project-assets/master/images/graphics/hue-slider-img-4.jpg"/>
            <div class="hue_content">
              <div>
              <header class="entry-header">
                <h1 class="entry-title">Go Hue Team</h1>
              </header>
              <p>
                Ut enim ad minim veniam, quis nostrud exercitation ullamco
                laboris nisi ut aliquip ex ea commodo consequat.
              </p>
              <input class="hue-button" onclick="window.location.href = '#'" type="button" value="Read More">
            </div></div>
          </li>
        </ul>

        ...
   ```
   
## Contributing

If you like to contribute to the project, pull requests are welcome. For any major changes, please open an issue to discuss the changes you intend to make.

## License

[GNU](https://choosealicense.com/licenses/gpl-3.0/)

