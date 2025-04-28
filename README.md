# it5001-assignment-5-solved
**TO GET THIS SOLUTION VISIT:** [IT5001 Assignment 5 Solved](https://www.ankitcodinghub.com/product/it5001-assignment/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119242&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IT5001  Assignment 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Required Files

• decipher_message_skeleton.py

• treasure_hunt_skeleton.py

• ancestor.py

• And a few encrypted map files ended in “.txt”

Part 1: Treasure maps

On a quest for treasure, you chance upon a weird, seemingly encrypted message. What could it mean?

esbtr dgh abzqg! vhe ghz yzqtcjxx qx qt btgesjz cbxepj!

Thankfully, you always have your handy translational dictionary with you.

{‘a’: ‘m’, ‘b’: ‘a’, ‘c’: ‘c’, ‘d’: ‘y’, ‘e’: ‘t’, ‘f’: ‘v’, ‘g’: ‘o’, ‘h’: ‘u’,

‘i’: ‘x’, ‘j’: ‘e’, ‘k’: ‘j’, ‘l’: ‘w’, ‘m’: ‘f’, ‘n’: ‘z’, ‘o’: ‘d’, ‘p’: ‘l’, ‘q’: ‘i’, ‘r’: ‘k’, ‘s’: ‘h’, ‘t’: ‘n’, ‘u’: ‘g’, ‘v’: ‘b’, ‘w’: ‘q’, ‘x’: ‘s’, ‘y’: ‘p’, ‘z’: ‘r’}

Translating each letter in the encrypted message using the dictionary, you get the final message:

thank you mario! but our princess is in another castle!

Your task

Write a function, decipher_message(msg,guide), that takes in two arguments to decipher the message “msg” with the dictionary “guide”. The message is a string and the guide is a dictionary. Your function should be able to translate any message with any dictionary and return the final deciphered message in a string.

Do note that your function should work for any arbitrary dictionary provided and should be not be hardcoded using the above example. Characters in the encrypted message which are not found in the translation dictionary (keys) can be taken as-is without having to do any substitution. You are guaranteed that there will be no capital letters in the encrypted string.

Sample run:

&gt;&gt;&gt; msg1e = “esbtr dgh abzqg! vhe ghz yzqtcjxx qx qt btgesjz cbxepj!”

&gt;&gt;&gt; print(decipher_message(msg1e,d1))

thank you mario! but our princess is in another castle!

Part 2: Find the Treasure!

After a long and arduous journey, you finally obtain the treasure map. However, much to your disappointment, the treasure map is encrypted as well.

ZZ1DDZDDD1DZD1ZZZ1ZD111223222B;+;44411DZ11DZ

Z1D1ZZD1111ZZ111ZDD1ZD04CFF0B+BB0220Z1DDZ1ZD

Z1ZZ11DDZZZ1ZZD1DZDZ1Z400F22+;+200202Z111Z11

1ZD1ZZZ1DD11DZ1Z1Z11Z24F22222B;BB40F2111DDZD

1DDZZZZZ1DDDZ1DDD1D1120402444+BBB44C2DZD1ZDD You turn to your handy translational dictionary once more.

d1 = {‘D’: ‘W’, ‘1’: ‘W’, ‘Z’: ‘W’, ‘C’: ‘T’, ‘3’: ‘T’, ‘F’: ‘T’, ‘0’: ‘.’, ‘2’:

‘.’, ‘4’: ‘.’, ‘B’: ‘^’, ‘+’: ‘^’, ‘;’: ‘^’, ‘Q’: ‘E’, ‘7’: ‘E’, ‘8’: ‘E’, ‘X’: ‘M’, ‘P’: ‘M’, ‘!’: ‘M’, ‘(‘: ‘:’, ‘)’: ‘:’, ‘9’: ‘:’, ‘*’: ‘ ‘, ‘|’: ‘ ‘, ‘#’:

‘ ‘}

With the dictionary, you should be able to decipher the above encrypted map into something like this:

WWWWWWWWWWWWWWWWWWWWWWW..T…^^^^…WWWWWWWW

WWWWWWWWWWWWWWWWWWWWWW..TTT.^^^^….WWWWWWWW

WWWWWWWWWWWWWWWWWWWWWW…T..^^^……WWWWWWW

WWWWWWWWWWWWWWWWWWWWW..T…..^^^^..T.WWWWWWW

WWWWWWWWWWWWWWWWWWWWW……..^^^^..T.WWWWWWW

You should have gotten the hint where the treasure is from the last question in Part 1!

Your task is to, first decrypt the map and then find the treasure.

decode_map(mapfile,ddict,outfile)

Such that mapfile and outfile are two filenames. Your function will read in mapfile and use the ddict to decrypt, and then store the result into outfile. For example, after

decode_map(‘encoded_map.txt’,d1,’decoded_map.txt’)

It should read in a file ‘encoded_map.txt’ and write the result file into ‘decoded_map.txt’ in your directory.

And the file ‘decoded_map.txt’ should contain the decrypted map like this (‘answer map.txt’):

Write a function find_treasure(mapfile) that reads in the file ‘mapfile’ and return the coordinates of the treasure in a tuple. For example:

Again, do note that your function should work for any arbitrary dictionary and encrypted map provided, and should be not be hardcoded using the above example. Row and column indexes in the map also start from 0 – that means the first, ‘top-most’ and ‘left-most’ cell on the map will correspond to the 0th row and the 0th column. You can assume that the map will have only one location of treasure.

Part 3: Ancestry trees

Given some ancestry information, such as the following:

Ben is Amy’s father,

Ben is also Tom’s father,

Amy is Frank’s mother,

We can easily construct the ‘graphical representation’ of the ancestry tree (right), and we can also construct a dictionary to represent our ancestry tree:

Here, the keys of the dictionary represent the ‘child’, while the values of the dictionary represent the ‘parent’. For example, ‘Ben’ is the ancestor of ‘Amy’, so our first entry is “‘Amy’: ’Ben’”. That’s why parent[‘Amy’] = Ben.

To simply this question, we assume that every name is unique, and every person has at most one parent. So, here is an example parent dictionary:

‘Ben’:’Howard’, ‘Howard’:’George’, ‘Frank’:’Amy’,

‘Joe’:’Bill’, ‘Bill’:’Mary’, ‘Mary’:’Philip’, ‘Simon’:’Bill’,

‘Zoe’:’Mary’}

Person A is an (indirect) ancestor of Person B if Person B is considered to be one of the many descendants of Person A. In the example ancestry tree given above, Howard is an ancestor of Amy, but Amy is not an ancestor of Tom. And that person himself is NOT his own ancestor. Your task is to write a function,

is_ancestor(name1,name2,pdict),

that takes in three arguments. The first two arguments are the names of people (strings), while the third argument is the parent dictionary mentioned above. The function should return the boolean value ‘True’ if the first person in the argument list is an ancestor of the second person, and ‘False’ if the first person in the argument list is not an ancestor of the second person.

Sample run:

&gt;&gt;&gt; is_ancestor(‘Howard’, ‘Amy’, parent)

True

&gt;&gt;&gt; is_ancestor(‘Amy’, ‘Tom’, parent) False

Two people are related if they share a common ancestor in the ancestry tree. In the example ancestry tree given above, Amy and Tom are related since they share a common ancestor, Ben, and Ben and Howard are related since they share a common ancestor, George. Write a function

If we were to introduce a new person, for example Luna, with no ties to anyone in the ancestry tree, Luna be considered to be not related to anyone in the ancestry tree. Write a function is_related(name1,name2,pdict) to check if the person with name1 is related to the person with name2 in the parent dictionary pdict.
