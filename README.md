# assignment2-Morgan
# Wyatt Morgan
### My favorite team sport is basketball
#### It is my favorite team sport because I like being able to dribble a ball around, doing different **tricks**, spinning it on my finger, etc. And it's is always so satisfying sinking a basket. Hearing the swish of the basket after a shot you took is just so **rewarding**, no matter who you are. It also is a great way to practice hand eye coordination because being able to do things unpredictably or without looking is very important in that sport.

---

## Chicago Bulls
1. Micheal Jordan
2. Scottie Pippen
3. Artis Gilmore
* Miami Heat
* LA Lakers
* Boston Celtics

[About Me](AboutMe.md)


---

#Tables
In this section we will be looking at 4 countries I think everyone should visit!

| Country Name | Why I Recommend it | Time to Spend There |
| --- | --- | --- |
| Germany | The country has very important history to how the world currently runs and they have very good deli meats | I would spend from 3 days to a week there |
| Canada | It's not too far from home but still a new area to check out and enjoy. Colder climates for those who enjoy them. | I would spend 3 days to a week here too |
| Italy | There's a large variety of great food options you can try here as well as a big change in architecture (mostly) from the US | I would spend 2 weeks here |
| Anywhere in "Basque" country in Spain/France | Full of people who have a lot of national pride and good food! | I would spend about a week here |

---

#Quotes

>I've got a list, we're gonna work down it, together. Number 1, I'm gonna bend something, something that was not meant to bend.
>>I'm gonna stop you right there because I'm not gonna make it to 2. I won't even make it to 1. I don't do well with pain, I stub my toe and I'm done for the day. *Deadpool 2 Writers*

>Hi, I'm looking for ray finkle... and a clean pair of shorts. *Ace Ventura Writers*

---

# Code Fencing

```
<button>
  Some
  <br>
  Text
</button>
```
<https://css-tricks.com/snippets/html/button-with-line-breaks/>

>I have a large file with line breaks and spaces. The file has text like as follows

Ampex 

Baofeng 

JBL 

Pioneer 

Sony 

1 BY ONE 
To read the file i wrote this

$array = explode("\n", file_get_contents('brands.txt'));

foreach($array as $line) {
    
    $html_code = '<div class="form-check">
  <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
  <label class="form-check-label d-flex justify-content-between align-items-center" for="exampleRadios1">'.
     $line
    .'<span class="badge bg-primary rounded-pill">1</span>
  </label>
</div>';
echo $html_code;

echo '<pre>';
//print_r($line);
echo '</pre>';
}
however my html output has an extra radio with value 1 after output the correct value. How can i output the correct value without the 1 showing as a radio button value?
<https://stackoverflow.com/questions/73671967/remove-white-space-from-text-file-with-line-breaks>

