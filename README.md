# DynamicSchedule
DynamicSchedule is a minimalistic, interactive schedule with reminders.

![Screenshot_1](/../readme_files/screenshot_1.png?raw=true)

Did you ever forget where you have your next remote lecture?

Did you forget that you have one more labs before you can go cook dinner?

#### This app should be just for you.

- Sound reminder for each starting/ending block (you can turn it off)
  - (![Screenshot_crop_1](/../readme_files/screenshot_crop_1.png?raw=true) / ![Screenshot_crop_2](/../readme_files/screenshot_crop_2.png?raw=true))
- Highlights the current block to help you get around more easily
  - ![Screenshot_3](/../readme_files/screenshot_3.png?raw=true)
- Easy templating current blocks (you can copy it, change a bit and place somewhere else)
- Works on mobile, small and large screens
- Works offline
- In just 1 file (ease of use and ease of sharing)
- No engines, no servers, just HTML, CSS and JS
- Dark mode 

<hr>

Previews:

<a href="https://htmlpreview.github.io/?https://github.com/GabenRulez/DynamicSchedule/blob/main/clean_schedule.html" target="_blank">Clean slate</a>

<a href="https://htmlpreview.github.io/?https://github.com/GabenRulez/DynamicSchedule/blob/main/template_schedule.html" target="_blank">Template</a> ( the data included is complete fictional )

###### It's not advised to download your schedule from those preview sites (the downloaded files might include some additional scripts, embedded by "htmlpreview.github.io"). 

<hr>

#### How to 

- Copy a block
  - Open "Modify plan" (bottom right corner)
    - ![Screenshot_crop_3](/../readme_files/screenshot_crop_3.png?raw=true)
  - Choose day and time of a block you want to copy and then press "LOAD"
    - ![Screenshot_4](/../readme_files/screenshot_4.png?raw=true)
  - You're gonna see, that the block was succesfully loaded and displayed on the bottom of the window. Also the form should be filled with that data. 
    - ![Screenshot_5](/../readme_files/screenshot_5.png?raw=true)
  - Then you can choose different day and time (same list as point 2.).
    - ![Screenshot_6](/../readme_files/screenshot_6.png?raw=true)
  - Now you should press "SAVE" button. You should see the block showing up in the selected space. WARNING: It will overwrite whatever was in that space, so use with caution.
  
<hr style="width: 50%">
  
- Move a block
  - Follow "How to Copy a block"
  - From the list choose the block you were coping.
    - ![Screenshot_5](/../readme_files/screenshot_5.png?raw=true)
  - Press "DELETE" button. 
  WARNING: Deleted block is deleted permanently, although you might have it's data inside your form. Use with caution.
  
<hr style="width: 50%"> 
 
- Save filled in schedule
  - Once you got all the blocks you need you just need to open "Modify plan".
    - ![Screenshot_crop_3](/../readme_files/screenshot_crop_3.png?raw=true)
  - Then you press "SAVE FILE" (right side, middle height). You should be greeted with the prompt to save a file.
    - ![Screenshot_7](/../readme_files/screenshot_7.png?raw=true)
  - The downloaded file will include everything you need. You can dispose of the original .html file now (every copy of the schedule is capable of generating more schedules).