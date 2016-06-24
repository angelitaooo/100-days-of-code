# 100-days-of-code

### Day 1
- Manipulating Complex Objects [link to Freecodecamp](https://www.freecodecamp.com/challenges/Manipulating%20Complex%20Objects?solution=%0Avar%20myMusic%20%3D%20%5B%0A%20%20%7B%0A%20%20%20%20%22artist%22%3A%20%22Billy%20Joel%22%2C%0A%20%20%20%20%22title%22%3A%20%22Piano%20Man%22%2C%0A%20%20%20%20%22release_year%22%3A%201973%2C%0A%20%20%20%20%22formats%22%3A%20%5B%20%0A%20%20%20%20%20%20%22CS%22%2C%20%0A%20%20%20%20%20%20%228T%22%2C%20%0A%20%20%20%20%20%20%22LP%22%20%5D%2C%0A%20%20%20%20%22gold%22%3A%20true%0A%20%20%7D%2C%0A%20%20%0A%20%7B%0A%20%20%20%20%22artist%22%3A%20%22coldplay%22%2C%0A%20%20%20%20%22title%22%3A%20%22viva%20la%20vida%22%2C%0A%20%20%20%20%22release_year%22%3A%202009%2C%0A%20%20%20%20%22formats%22%3A%20%5B%0A%20%20%20%20%20%20%22cd%22%2C%0A%20%20%20%20%20%20%22dvd%22%2C%0A%20%20%20%20%20%20%22lp%22%0A%20%20%20%20%5D%0A%20%20%7D%0A%20%20%2F%2F%20Add%20record%20here%0A%5D%3B%0A%0A)
- Accessing Nested Objects [link to Freecodecamp](https://www.freecodecamp.com/challenges/Accessing%20Nested%20Objects?solution=%0A%2F%2F%20Setup%0Avar%20myStorage%20%3D%20%7B%0A%20%20%22car%22%3A%20%7B%0A%20%20%20%20%22inside%22%3A%20%7B%0A%20%20%20%20%20%20%22glove%20box%22%3A%20%22maps%22%2C%0A%20%20%20%20%20%20%22passenger%20seat%22%3A%20%22crumbs%22%0A%20%20%20%20%20%7D%2C%0A%20%20%20%20%22outside%22%3A%20%7B%0A%20%20%20%20%20%20%22trunk%22%3A%20%22jack%22%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line%0A%0Avar%20gloveBoxContents%20%3D%20myStorage.car.inside%5B%22glove%20box%22%5D%3B%20%2F%2F%20Change%20this%20line%0A%0A)
- Accessing Nested Arrays [link to Freecodecamp](https://www.freecodecamp.com/challenges/Accessing%20Nested%20Arrays?solution=%0A%2F%2F%20Setup%0Avar%20myPlants%20%3D%20%5B%0A%20%20%7B%20%0A%20%20%20%20type%3A%20%22flowers%22%2C%0A%20%20%20%20list%3A%20%5B%0A%20%20%20%20%20%20%22rose%22%2C%0A%20%20%20%20%20%20%22tulip%22%2C%0A%20%20%20%20%20%20%22dandelion%22%0A%20%20%20%20%5D%0A%20%20%7D%2C%0A%20%20%7B%0A%20%20%20%20type%3A%20%22trees%22%2C%0A%20%20%20%20list%3A%20%5B%0A%20%20%20%20%20%20%22fir%22%2C%0A%20%20%20%20%20%20%22pine%22%2C%0A%20%20%20%20%20%20%22birch%22%0A%20%20%20%20%5D%0A%20%20%7D%20%20%0A%5D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line%0A%0Avar%20secondTree%20%3D%20myPlants%5B1%5D.list%5B1%5D%3B%20%2F%2F%20Change%20this%20line%0A%0A)

### Day 2
- Iterate with JavaScript For [Link](https://www.freecodecamp.com/challenges/Iterate%20with%20JavaScript%20For%20Loops?solution=%0A%2F%2F%20Example%0Avar%20ourArray%20%3D%20%5B%5D%3B%0A%0Afor%20(var%20i%20%3D%200%3B%20i%20%3C%205%3B%20i%2B%2B)%20%7B%0A%20%20ourArray.push(i)%3B%0A%7D%0A%0A%2F%2F%20Setup%0Avar%20myArray%20%3D%20%5B%5D%3B%0A%0Afor%20(var%20i%20%3D%201%3B%20i%20%3C%206%3B%20i%2B%2B)%20%7B%0A%20%20myArray.push(i)%3B%0A%7D%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A%0A)
- Iterate Odd Numbers With a For Loop	[Link](https://www.freecodecamp.com/challenges/Iterate%20Odd%20Numbers%20With%20a%20For%20Loop?solution=%0A%2F%2F%20Example%0Avar%20ourArray%20%3D%20%5B%5D%3B%0A%0Afor%20(var%20i%20%3D%200%3B%20i%20%3C%2010%3B%20i%20%2B%3D%202)%20%7B%0A%20%20ourArray.push(i)%3B%0A%7D%0A%0A%2F%2F%20Setup%0Avar%20myArray%20%3D%20%5B%5D%3B%0A%20%20for%20(var%20i%20%3D%201%3B%20i%20%3C10%3B%20i%2B%3D2)%7B%0A%20%20%20%20myArray.push(i)%3B%0A%20%20%7D%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A%0A)
- Count Backwards With a For Loop	[Link](https://www.freecodecamp.com/challenges/Count%20Backwards%20With%20a%20For%20Loop?solution=%0A%2F%2F%20Example%0Avar%20ourArray%20%3D%20%5B%5D%3B%0A%0Afor%20(var%20i%20%3D%2010%3B%20i%20%3E%200%3B%20i%20-%3D%202)%20%7B%0A%20%20ourArray.push(i)%3B%0A%7D%0A%0A%2F%2F%20Setup%0Avar%20myArray%20%3D%20%5B%5D%3B%0A%20%20for%20(var%20i%20%3D%209%3B%20i%20%3E%200%3B%20i%20-%3D%202)%7B%0A%20%20%20%20myArray.push(i)%3B%0A%20%20%7D%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A)
- Iterate Through an Array with a For Loop	[Link](https://www.freecodecamp.com/challenges/Iterate%20Through%20an%20Array%20with%20a%20For%20Loop?solution=%0A%2F%2F%20Example%0Avar%20ourArr%20%3D%20%5B%209%2C%2010%2C%2011%2C%2012%5D%3B%0Avar%20ourTotal%20%3D%200%3B%0A%0Afor%20(var%20i%20%3D%200%3B%20i%20%3C%20ourArr.length%3B%20i%2B%2B)%20%7B%0A%20%20ourTotal%20%2B%3D%20ourArr%5Bi%5D%3B%0A%7D%0A%0A%2F%2F%20Setup%0Avar%20myArr%20%3D%20%5B%202%2C%203%2C%204%2C%205%2C%206%5D%3B%0Avar%20total%20%3D%200%3B%0Afor%20(var%20i%20%3D%200%3B%20i%20%3C%20myArr.length%3B%20i%2B%2B)%7B%0A%20%20total%20%2B%3D%20myArr%5Bi%5D%3B%0A%7D%0A%2F%2F%20Only%20change%20code%20below%20this%20line%0A%0A%0A)
- Nesting For Loops	[Link](https://www.freecodecamp.com/challenges/Nesting%20For%20Loops?solution=%0Afunction%20multiplyAll(arr)%20%7B%0A%20%20var%20product%20%3D%201%3B%0A%20%20%2F%2F%20Only%20change%20code%20below%20this%20line%0A%20%20for%20(var%20i%20%3D%200%3B%20i%20%3C%20arr.length%3B%20i%2B%2B)%7B%0A%20%20%20%20%20%20for%20(var%20j%20%3D%200%3B%20j%20%3C%20arr%5Bi%5D.length%3B%20j%2B%2B)%20%7B%0A%20%20%20%20%20%20%20%20console.log(arr%5Bi%5D%5Bj%5D)%3B%0A%20%20%20%20%20%20%20%20product%20%3D%20product%20*%20arr%5Bi%5D%5Bj%5D%3B%0A%20%20%20%20%20%20%7D%0A%20%20%7D%0A%20%20%2F%2F%20Only%20change%20code%20above%20this%20line%0A%20%20return%20product%3B%0A%7D%0A%0A%2F%2F%20Modify%20values%20below%20to%20test%20your%20code%0AmultiplyAll(%5B%5B1%2C2%5D%2C%5B3%2C4%5D%2C%5B5%2C6%2C7%5D%5D)%3B%0A%0A)
- Iterate with JavaScript While Loops	[Link](https://www.freecodecamp.com/challenges/Iterate%20with%20JavaScript%20While%20Loops?solution=%0A%2F%2F%20Setup%0Avar%20myArray%20%3D%20%5B%5D%3B%0Avar%20i%20%3D%200%3B%0Awhile(%20i%20%3C%205)%20%7B%0A%20%20myArray.push(i)%3B%0A%20%20i%2B%2B%3B%0A%7D%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A%0A)
- Generate Random Fractions with JavaScript	[Link](https://www.freecodecamp.com/challenges/Generate%20Random%20Fractions%20with%20JavaScript?solution=%0Afunction%20randomFraction()%20%7B%0A%0A%20%20%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A%20%20return%20Math.random()%3B%0A%0A%20%20%2F%2F%20Only%20change%20code%20above%20this%20line.%0A%7D%0A)
- Generate Random Whole Numbers with JavaScript [Link](https://www.freecodecamp.com/challenges/Generate%20Random%20Whole%20Numbers%20with%20JavaScript?solution=%0Avar%20randomNumberBetween0and19%20%3D%20Math.floor(Math.random()%20*%2010)%3B%0A%0Afunction%20randomWholeNum()%20%7B%0A%0A%20%20%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A%20%20return%20Math.floor(Math.random())%3B%0A%7D%0A)
- Sift through Text with Regular Expressions [Link](https://www.freecodecamp.com/challenges/Sift%20through%20Text%20with%20Regular%20Expressions?solution=%0A%2F%2F%20Setup%0Avar%20testString%20%3D%20%22Ada%20Lovelace%20and%20Charles%20Babbage%20designed%20the%20first%20computer%20and%20the%20software%20that%20would%20have%20run%20on%20it.%22%3B%0A%0A%2F%2F%20Example%0Avar%20expressionToGetSoftware%20%3D%20%2Fsoftware%2Fgi%3B%0Avar%20softwareCount%20%3D%20testString.match(expressionToGetSoftware).length%3B%0A%20%20%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0Avar%20expression%20%3D%20%2Fand%2Fgi%3B%20%20%2F%2F%20Change%20this%20Line%0A%0A%2F%2F%20Only%20change%20code%20above%20this%20line%0A%0A%2F%2F%20This%20code%20counts%20the%20matches%20of%20expression%20in%20testString%0Avar%20andCount%20%3D%20testString.match(expression).length%3B%0A%0A)
- Find Numbers with Regular Expressions	[Link](https://www.freecodecamp.com/challenges/Find%20Numbers%20with%20Regular%20Expressions?solution=%0A%2F%2F%20Setup%0Avar%20testString%20%3D%20%22There%20are%203%20cats%20but%204%20dogs.%22%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0Avar%20expression%20%3D%20%2F%5Cd%2B%2Fg%3B%20%20%2F%2F%20Change%20this%20line%0A%0A%2F%2F%20Only%20change%20code%20above%20this%20line%0A%0A%2F%2F%20This%20code%20counts%20the%20matches%20of%20expression%20in%20testString%0Avar%20digitCount%20%3D%20testString.match(expression).length%3B%0A)
- Find Whitespace with Regular Expressions [Link](https://www.freecodecamp.com/challenges/Find%20Whitespace%20with%20Regular%20Expressions?solution=%0A%2F%2F%20Setup%0Avar%20testString%20%3D%20%22How%20many%20spaces%20are%20there%20in%20this%20sentence%3F%22%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0Avar%20expression%20%3D%20%2F%5Cs%2B%2Fg%3B%20%20%2F%2F%20Change%20this%20line%0A%0A%2F%2F%20Only%20change%20code%20above%20this%20line%0A%0A%2F%2F%20This%20code%20counts%20the%20matches%20of%20expression%20in%20testString%0Avar%20spaceCount%20%3D%20testString.match(expression).length%3B%0A)
- Invert Regular Expression Matches with JavaScript [Link](https://www.freecodecamp.com/challenges/Invert%20Regular%20Expression%20Matches%20with%20JavaScript?solution=%0A%2F%2F%20Setup%0Avar%20testString%20%3D%20%22How%20many%20non-space%20characters%20are%20there%20in%20this%20sentence%3F%22%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0Avar%20expression%20%3D%20%2F%5CS%2Fg%3B%20%20%2F%2F%20Change%20this%20line%0A%0A%2F%2F%20Only%20change%20code%20above%20this%20line%0A%0A%2F%2F%20This%20code%20counts%20the%20matches%20of%20expression%20in%20testString%0Avar%20nonSpaceCount%20%3D%20testString.match(expression).length%3B%0A)
- Record Collection [Link](https://www.freecodecamp.com/challenges/Record%20Collection?solution=%0A%2F%2F%20Setup%0Avar%20collection%20%3D%20%7B%0A%20%20%20%20%222548%22%3A%20%7B%0A%20%20%20%20%20%20%22album%22%3A%20%22Slippery%20When%20Wet%22%2C%0A%20%20%20%20%20%20%22artist%22%3A%20%22Bon%20Jovi%22%2C%0A%20%20%20%20%20%20tracks%3A%20%5B%20%0A%20%20%20%20%20%20%20%20%22Let%20It%20Rock%22%2C%20%0A%20%20%20%20%20%20%20%20%22You%20Give%20Love%20a%20Bad%20Name%22%20%0A%20%20%20%20%20%20%5D%0A%20%20%20%20%7D%2C%0A%20%20%20%20%222468%22%3A%20%7B%0A%20%20%20%20%20%20%22album%22%3A%20%221999%22%2C%0A%20%20%20%20%20%20%22artist%22%3A%20%22Prince%22%2C%0A%20%20%20%20%20%20%22tracks%22%3A%20%5B%20%0A%20%20%20%20%20%20%20%20%221999%22%2C%20%0A%20%20%20%20%20%20%20%20%22Little%20Red%20Corvette%22%20%0A%20%20%20%20%20%20%5D%0A%20%20%20%20%7D%2C%0A%20%20%20%20%221245%22%3A%20%7B%0A%20%20%20%20%20%20%22artist%22%3A%20%22Robert%20Palmer%22%2C%0A%20%20%20%20%20%20%22tracks%22%3A%20%5B%20%5D%0A%20%20%20%20%7D%2C%0A%20%20%20%20%225439%22%3A%20%7B%0A%20%20%20%20%20%20%22album%22%3A%20%22ABBA%20Gold%22%0A%20%20%20%20%7D%0A%7D%3B%0A%2F%2F%20Keep%20a%20copy%20of%20the%20collection%20for%20tests%0Avar%20collectionCopy%20%3D%20JSON.parse(JSON.stringify(collection))%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line%0Afunction%20updateRecords(id%2C%20prop%2C%20value)%20%7B%0A%20%20if%20(collection%5Bid%5D.hasOwnProperty(prop))%20%7B%0A%20%20%20%20%0A%20%20%20%20if%20(value)%20%7B%0A%20%20%20%20%20%20%0A%20%20%20%20%20%20if%20(prop%20%3D%3D%3D%20%22tracks%22)%20%7B%0A%20%20%20%20%20%20%20%20%0A%20%20%20%20%20%20%20%20collection%5Bid%5D%5Bprop%5D.push(value)%3B%0A%20%20%20%20%20%20%20%20%0A%20%20%20%20%20%20%7D%20else%20%7B%0A%20%20%20%20%20%20%20%20%0A%20%20%20%20%20%20%20%20%20collection%5Bid%5D%5Bprop%5D%20%3D%20value%3B%20%0A%20%20%20%20%20%20%20%20%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%20%0A%20%20%20%20%7D%20else%20%7B%0A%20%20%20%20%20%20%0A%20%20%20%20%20%20delete%20collection%5Bid%5D%5Bprop%5D%3B%0A%20%20%20%20%0A%20%20%20%20%7D%0A%20%20%20%20%20%20%0A%20%20%7D%20else%20%7B%0A%20%20%20%20%0A%20%20%20%20if%20(prop%20%3D%3D%3D%20%22tracks%22)%20%7B%0A%20%20%20%20%20%20%0A%20%20%20%20%20%20collection%5Bid%5D%5Bprop%5D%20%3D%20%5Bvalue%5D%3B%0A%20%20%20%20%20%20%0A%20%20%20%20%7D%20else%20%7B%0A%20%20%20%20%20%20%0A%20%20%20%20%20%20%20collection%5Bid%5D%5Bprop%5D%20%3D%20value%3B%0A%20%20%20%20%20%20%0A%20%20%20%20%7D%0A%20%20%20%20%0A%20%20%7D%0A%0A%20%20return%20collection%3B%0A%7D%0A%0A%2F%2F%20Alter%20values%20below%20to%20test%20your%20code%0AupdateRecords(1245%2C%20%22tracks%22%2C%20%22Addicted%20to%20Love%22)%3B%0A%0A)
 
### Day 3
- Profile Lookup [link](https://www.freecodecamp.com/challenges/Profile%20Lookup?solution=%0A%2F%2FSetup%0Avar%20contacts%20%3D%20%5B%0A%20%20%20%20%7B%0A%20%20%20%20%20%20%20%20%22firstName%22%3A%20%22Akira%22%2C%0A%20%20%20%20%20%20%20%20%22lastName%22%3A%20%22Laine%22%2C%0A%20%20%20%20%20%20%20%20%22number%22%3A%20%220543236543%22%2C%0A%20%20%20%20%20%20%20%20%22likes%22%3A%20%5B%22Pizza%22%2C%20%22Coding%22%2C%20%22Brownie%20Points%22%5D%0A%20%20%20%20%7D%2C%0A%20%20%20%20%7B%0A%20%20%20%20%20%20%20%20%22firstName%22%3A%20%22Harry%22%2C%0A%20%20%20%20%20%20%20%20%22lastName%22%3A%20%22Potter%22%2C%0A%20%20%20%20%20%20%20%20%22number%22%3A%20%220994372684%22%2C%0A%20%20%20%20%20%20%20%20%22likes%22%3A%20%5B%22Hogwarts%22%2C%20%22Magic%22%2C%20%22Hagrid%22%5D%0A%20%20%20%20%7D%2C%0A%20%20%20%20%7B%0A%20%20%20%20%20%20%20%20%22firstName%22%3A%20%22Sherlock%22%2C%0A%20%20%20%20%20%20%20%20%22lastName%22%3A%20%22Holmes%22%2C%0A%20%20%20%20%20%20%20%20%22number%22%3A%20%220487345643%22%2C%0A%20%20%20%20%20%20%20%20%22likes%22%3A%20%5B%22Intriguing%20Cases%22%2C%20%22Violin%22%5D%0A%20%20%20%20%7D%2C%0A%20%20%20%20%7B%0A%20%20%20%20%20%20%20%20%22firstName%22%3A%20%22Kristian%22%2C%0A%20%20%20%20%20%20%20%20%22lastName%22%3A%20%22Vos%22%2C%0A%20%20%20%20%20%20%20%20%22number%22%3A%20%22unknown%22%2C%0A%20%20%20%20%20%20%20%20%22likes%22%3A%20%5B%22Javascript%22%2C%20%22Gaming%22%2C%20%22Foxes%22%5D%0A%20%20%20%20%7D%0A%5D%3B%0A%0A%0Afunction%20lookUpProfile(firstName%2C%20prop)%7B%0A%2F%2F%20Only%20change%20code%20below%20this%20line%0A%20%20for%20(var%20i%20%3D%200%3B%20i%20%3C%20contacts.length%3B%20i%2B%2B)%20%7B%0A%20%20%20%20%0A%20%20%20%20if%20(contacts%5Bi%5D.firstName%20%3D%3D%3D%20firstName)%20%7B%0A%20%20%20%20%20%20if%20(contacts%5Bi%5D.hasOwnProperty(prop))%20%7B%0A%20%20%20%20%20%20%20%20return%20contacts%5Bi%5D%5Bprop%5D%3B%0A%20%20%20%20%20%20%7D%20else%20%7B%0A%20%20%20%20%20%20%20%20return%20%22No%20such%20property%22%3B%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%7D%0A%0A%20%20%7D%0A%20%20%0A%20%20return%20%22No%20such%20contact%22%3B%0A%2F%2F%20Only%20change%20code%20above%20this%20line%0A%7D%0A%0A%2F%2F%20Change%20these%20values%20to%20test%20your%20function%0AlookUpProfile(%22Akira%22%2C%20%22address%22)%3B%0A)
- Generate Random Whole Numbers within a Range [link](https://www.freecodecamp.com/challenges/Generate%20Random%20Whole%20Numbers%20within%20a%20Range?solution=%0A%2F%2F%20Example%0Afunction%20ourFunction(ourMin%2C%20ourMax)%20%7B%0A%0A%20%20return%20Math.floor(Math.random()%20*%20(ourMax%20-%20ourMin%20%2B%201))%20%2B%20ourMin%3B%0A%7D%0A%0AourFunction(1%2C%209)%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0Afunction%20randomRange(myMin%2C%20myMax)%20%7B%0A%0A%20%20return%20Math.floor(Math.random()%20*%20(myMax%20-%20myMin%20%2B%201))%20%2B%20myMin%3B%20%2F%2F%20Change%20this%20line%0A%0A%7D%0A%0A%2F%2F%20Change%20these%20values%20to%20test%20your%20function%0Avar%20myRandom%20%3D%20randomRange(5%2C%2015)%3B%0A)

#### Day 4
- Freecodecamp Tribute Page project. View revisions for June 23. [Gist](https://gist.github.com/angelitaooo/cf789687f02a1d59361c21d4805876c8/revisions)
