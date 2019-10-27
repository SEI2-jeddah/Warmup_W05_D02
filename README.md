# Warmup_W05_D02

## React State Practice

![](https://66.media.tumblr.com/70cd59c666abdc6ae0e12a5fcbbfbe96/tumblr_nti3ongAp31uev087o2_400.gif)

Create a react app that displays all the student names, where the following happens:

1)
- If you click on a name it turns red.
- The following image is displayed "http://getdrawings.com/free-icon-bw/hulk-icon-21.png"
- The message `I am the mighty _student_name, How dare you touch me!!?` is displayed under it. 

2)
- If you right click on a name it turns blue. 
- The following image is displayed "https://cdn11.bigcommerce.com/s-sq9zkarfah/images/stencil/350x350/products/117228/204948/Hulk-379-Decal-Sticker__73044.1511165171.jpg?c=2"
- The message `Stop. Poking. Around!!` is displayed under it. 


3)
- If you double click a name it turns green.
- The following image is displayed "https://cdn11.bigcommerce.com/s-sq9zkarfah/images/stencil/1280x1280/products/85440/182141/Hulk-Fist-Decal-Sticker__21739.1511149680.jpg?c=2?imbypass=on"
- The message `STOP IT!!!`  is displayed under it.
   
4)
- the message `STOP IT!!!` disappears after a second and the name goes back to black.

____

for your intial state use the following :
````
state = {
    className: "",
    content: "",
    image:
      "https://cdn0.iconfinder.com/data/icons/characters-2-2-outlined/227/hulk-superhero-marvel-character-avatar-smileface-profile-512.png"
  };

````
