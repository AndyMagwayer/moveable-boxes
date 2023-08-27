# moveable-boxes

![Image alt](https://github.com/{username}/{repository}/raw/{branch}/{path}/image.png)

## Deploy:
https://moveable-boxes-magamed.netlify.app/


## For doing this project:

Issue: This post is regarding the drop down boxes, they currently are fixed in place. I would like it so they are directly under each other, and then when you click expand on one the other is pushed down. How would i go about doing this?

Setup: Each box is its own div (box1 through to box6), and this is in two divs (top and bottom (for the corresponding row), this is then inside an about div.

CSS: This is the CSS I used: http://test.getfamo.us/css/screen.css

Im fairly certain there should be a way to do it with less code as well. But anyway Im more worried about having it so the box below moves down when the box expands. The code in question is under "/* ABOUT */" so if you search for that it should come up.

Thanks very much for any help offered! (expand coded in jquery if relevant)

<br>
I hope I understand you... :) Than you need to separate your drop downs on 3 columns so place 3 di inside one within style "float:left", than in each div place 2 drop downs... in this case when you expand one of the drop down it will effect only on current column – 
Nikita Holovach
 Feb 17, 2014 at 23:44 
I mean so when I expand the top div, the bottom div then moves down automatically :) as currently it stays in place. Thanks for trying to help though! – 
getfamous
 Feb 17, 2014 at 23:51
oh, this is because your "position: absolute;" at #box try use float:left instead – 
Nikita Holovach
 Feb 18, 2014 at 0:02 

