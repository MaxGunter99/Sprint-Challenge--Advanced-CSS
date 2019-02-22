so the rest of my read me page randomly vanished so I made this one to answer questions

1.What is the difference between an adaptive website and a fully responsive website?

An adaptive website will respond to different systems (mobile, desktop, and tablet) in the same way, a responsive website will be more fluid with its responses to the settings that the user has like using large text as the default text.

2.Describe what it means to be mobile first vs desktop first.

Mobile first focuses on the mobile version of the website first and then expands to desktop. Desktop first is reverse of that, they start with a desktop website then minimize to tablet and mobile.

3.What does font-size: 62.5% in the html tag do for us when using rem units?

It allows the user setting to affect the font size on your page, it adjusts properly.

4.How would you describe preprocessing to someone new to CSS?

Processing is a cleaner way to write your CSS code. usually writing on one CSS page can get a little busy and confusing, but processing allows you to seperate out the HTMl and you can work on it one piece at a time, so you should know exactly what you are doing and not memorizing where everything is/ having to read over your entire CSS everytime you want to make a change. also if you have a huge website with over 4000 lines it can get very very confusing. Less is very very useful.

5.What is your favorite concept in preprocessing? What is the concept that gives you the most trouble?

My favorite concept in processing has to be activating less, then importing all the .less files. A fun thing to do in processing is nesting in your CSS, say you have a button in your css and you want to nest a hover elelment. instead of creating a whole new selector you can just nest inside of it and apply hover to the parent function by using "&:hover {}". something that i have struggled with is trying to figure out how to use the @media @mobile function. ive tried a ton of ways to do it (@mobile: ( max-width: 500px); and @mobile: ~"(max-width: 500px)";) as mixins but Im yet to figure it out. I usually have to just nest the media tag.
