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

#### Day 5
- Pioneras developers profile page [pull request](https://github.com/NavePionera/navepionera.github.io/pull/1)

#### Day 6
- Freecodecamp Tribute Page project. View revisions for June 26.
[Gist](https://gist.github.com/angelitaooo/cf789687f02a1d59361c21d4805876c8/revisions)
- [Tribute page codepen](http://codepen.io/angelitaooo/pen/KMawOm)

#### Day 7
- Declare JavaScript Objects as Variables	[Link](https://www.freecodecamp.com/challenges/Declare%20JavaScript%20Objects%20as%20Variables?solution=%0Avar%20car%20%3D%20%7B%0A%20%20%22wheels%22%3A4%2C%0A%20%20%22engines%22%3A1%2C%0A%20%20%22seats%22%3A5%0A%7D%3B%0A%0Avar%20motorBike%20%3D%20%7B%0A%20%20%22wheels%22%3A2%2C%0A%20%20%22engines%22%3A1%2C%0A%20%20%22seats%22%3A1%0A%20%20%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%7D%3B%0A)
- Construct JavaScript Objects with Functions	[Link](https://www.freecodecamp.com/challenges/Construct%20JavaScript%20Objects%20with%20Functions?solution=%0Avar%20Car%20%3D%20function()%20%7B%0A%20%20this.wheels%20%3D%204%3B%0A%20%20this.engines%20%3D%201%3B%0A%20%20this.seats%20%3D%201%3B%0A%7D%3B%0A%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0Avar%20MotorBike%20%3D%20function()%20%7B%0A%20%20this.wheels%20%3D%202%3B%0A%20%20this.engines%20%3D%201%3B%0A%20%20this.seats%20%3D%201%3B%0A%7D%3B%0A)	
- Make Instances of Objects with a Constructor	[Link](https://www.freecodecamp.com/challenges/Make%20Instances%20of%20Objects%20with%20a%20Constructor%20Function?solution=%0Avar%20Car%20%3D%20function()%20%7B%0A%20%20this.wheels%20%3D%204%3B%0A%20%20this.engines%20%3D%201%3B%0A%20%20this.seats%20%3D%201%3B%0A%7D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0Avar%20myCar%20%3D%20new%20Car()%3B%0AmyCar.nickname%20%3D%20%22carlos%22%3B%0A)
- Make Unique Objects by Passing Parameters to our Constructor [Link](https://www.freecodecamp.com/challenges/Make%20Unique%20Objects%20by%20Passing%20Parameters%20to%20our%20Constructor?solution=%0Avar%20Car%20%3D%20function(wheels%2C%20seats%2C%20engines)%20%7B%0A%20%20%2F%2FChange%20this%20constructor%0A%20%20this.wheels%20%3D%20wheels%3B%0A%20%20this.seats%20%3D%20seats%3B%0A%20%20this.engines%20%3D%20engines%3B%0A%7D%3B%0A%0A%2F%2FTry%20it%20out%20here%0Avar%20myCar%20%3D%20new%20Car(4%2C%204%2C%202)%3B%0A)	
- Make Object Properties Private	[Link](https://www.freecodecamp.com/challenges/Make%20Object%20Properties%20Private?solution=%0Avar%20Car%20%3D%20function()%20%7B%0A%20%20%2F%2F%20this%20is%20a%20private%20variable%0A%20%20var%20speed%20%3D%2010%3B%0A%0A%20%20%2F%2F%20these%20are%20public%20methods%0A%20%20this.accelerate%20%3D%20function(change)%20%7B%0A%20%20%20%20speed%20%2B%3D%20change%3B%0A%20%20%7D%3B%0A%0A%20%20this.decelerate%20%3D%20function()%20%7B%0A%20%20%20%20speed%20-%3D%205%3B%0A%20%20%7D%3B%0A%0A%20%20this.getSpeed%20%3D%20function()%20%7B%0A%20%20%20%20return%20speed%3B%0A%20%20%7D%3B%0A%7D%3B%0A%0Avar%20Bike%20%3D%20function()%20%7B%0A%0A%20%20var%20gear%20%3D%203%3B%0A%20%20%0A%20%20this.setGear%20%3D%20function(val)%7B%0A%20%20%20%20gear%20%3D%20val%3B%0A%20%20%7D%3B%0A%20%20%0A%20%20this.getGear%20%3D%20function()%20%7B%0A%20%20%20%20return%20gear%3B%0A%20%20%7D%3B%0A%20%20%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A%7D%3B%0A%0Avar%20myCar%20%3D%20new%20Car()%3B%0A%0Avar%20myBike%20%3D%20new%20Bike()%3B%0A%0A)

#### Day 8
- Iterate over Arrays with map [link](https://www.freecodecamp.com/challenges/Iterate%20over%20Arrays%20with%20map?solution=%0Avar%20oldArray%20%3D%20%5B1%2C2%2C3%2C4%2C5%5D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0Avar%20newArray%20%3D%20oldArray.map(function(val)%20%7B%0A%20%20%20return%20val%20%2B%203%3B%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%0A%20%7D)%3B%0A)
- Condense arrays with reduce [link](https://www.freecodecamp.com/challenges/Condense%20arrays%20with%20reduce?solution=%0Avar%20array%20%3D%20%5B4%2C5%2C6%2C7%2C8%5D%3B%0Avar%20singleVal%20%3D%200%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0AsingleVal%20%3D%20array.reduce(function(previousVal%2C%20currentVal)%20%7B%0A%20%20return%20previousVal%20%2B%20currentVal%3B%0A%7D%2C%200)%3B%0A)

#### Day 9
- Condense arrays with reduce	 [Link](https://www.freecodecamp.com/challenges/Condense%20arrays%20with%20reduce?solution=%0Avar%20array%20%3D%20%5B4%2C5%2C6%2C7%2C8%5D%3B%0Avar%20singleVal%20%3D%200%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0AsingleVal%20%3D%20array.reduce(function(previousVal%2C%20currentVal)%20%7B%0A%20%20return%20previousVal%20%2B%20currentVal%3B%0A%7D%2C%200)%3B%0A)
- Filter Arrays with filter	[Link](https://www.freecodecamp.com/challenges/Filter%20Arrays%20with%20filter?solution=%0Avar%20oldArray%20%3D%20%5B1%2C2%2C3%2C4%2C5%2C6%2C7%2C8%2C9%2C10%5D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0Avar%20newArray%20%3D%20oldArray.filter(function(val)%20%7B%0A%20%20return%20val%20%3C%206%3B%0A%7D)%3B%0A)
- Sort Arrays with sort	[Link](https://www.freecodecamp.com/challenges/Sort%20Arrays%20with%20sort?solution=%0Avar%20array%20%3D%20%5B1%2C%2012%2C%2021%2C%202%5D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0Aarray.sort(function(a%2C%20b)%20%7B%0A%20%20return%20b%20-%20a%3B%20%20%20%20%20%20%20%20%20%20%0A%7D)%3B%0A)
- Reverse Arrays with reverse [Link](https://www.freecodecamp.com/challenges/Reverse%20Arrays%20with%20reverse?solution=%0Avar%20array%20%3D%20%5B1%2C2%2C3%2C4%2C5%2C6%2C7%5D%3B%0Avar%20newArray%20%3D%20%5B%5D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0AnewArray%20%3D%20array.reverse()%3B%0A)
- Concatenate Arrays with concat	[Link](https://www.freecodecamp.com/challenges/Concatenate%20Arrays%20with%20concat?solution=%0Avar%20oldArray%20%3D%20%5B1%2C2%2C3%5D%3B%0Avar%20newArray%20%3D%20%5B%5D%3B%0A%0Avar%20concatMe%20%3D%20%5B4%2C5%2C6%5D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0AnewArray%20%3D%20oldArray.concat(concatMe)%3B%0A)
- Split Strings with split	[Link](https://www.freecodecamp.com/challenges/Split%20Strings%20with%20split?solution=%0Avar%20string%20%3D%20%22Split%20me%20into%20an%20array%22%3B%0Avar%20array%20%3D%20%5B%5D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0Aarray%20%3D%20string.split(%27%20%27)%3B%0A)
- Join Strings with join	[Link](https://www.freecodecamp.com/challenges/Join%20Strings%20with%20join?solution=%0Avar%20joinMe%20%3D%20%5B%22Split%22%2C%22me%22%2C%22into%22%2C%22an%22%2C%22array%22%5D%3B%0Avar%20joinedString%20%3D%20%27%27%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0AjoinedString%20%3D%20joinMe.join(%22%20%22)%3B%0A)
- Get Set for our Algorithm Challenges [Link](https://www.freecodecamp.com/challenges/Get%20Set%20for%20our%20Algorithm%20Challenges)

#### Day 10
- Introduction to objects, We've come a long, long...[Link to Gist](https://gist.github.com/23eb9587126cc44e61b5a1b9db29ce20)
- Introduction to objects, Through the hard times... [Link to Gist](https://gist.github.com/aa30cd1ded3b6590a4ffb8027f813456)
- Introduction to objects, ...And the good! [Link to Gist](https://gist.github.com/5a7abe5aad3d3e7ccf7772b6202e65c0)

#### Day 11
- Codecademy, Introduction to objects, I have to celebrate you baby [Link to Gist](https://gist.github.com/71a1271576a60eccb8705e8343275951)
-  Codecademy, Introduction to objects, Properties [Link to Gist](https://gist.github.com/1c71da9d6532ae46615fa4945399376d)
-  Codecademy, Introduction to objects, Accessing Properties [Link to Gist](https://gist.github.com/738082f5793be63dd363da8b7ade94ae)
-  Codecademy, Introduction to objects, Accessing Properties, Part 2[Link to Gist](https://gist.github.com/d5260c51fb2ad4b984a5a05198dc27b9)
-  Codecademy, Introduction to objects, Another Way to Create [Link to Gist](https://gist.github.com/d6dfe94d4d0cf7ff05170b667b121b2e)
-  Codecademy, Introduction to objects, Putting it all together[Link to Gist](https://gist.github.com/ad44982713b7ce581b679580f8abed00)
-  Codecademy, Introduction to objects, More Practice Making Objects[Link to Gist](https://gist.github.com/5835b85bddf6db2f93201d87c7c75684)
-  Codecademy, Introduction to objects, Function Review[Link to Gist](https://gist.github.com/1330040b78886dc3b41ece77ccc783c3)
- Codecademy, Introduction to objects, Why Are Methods Important?[Link to Gist](https://gist.github.com/a974f87b119bd4083cd72284b91112a7)
- Codecademy, Introduction to objects, The "this" Keyword [Link to Gist](https://gist.github.com/49213cd7978c4917b369ea6989b940c3)
- Codecademy, Introduction to objects,"This" Works for Everyone
 [Link to Gist](https://gist.github.com/fd29810212076eef8b5cb1e9f85de5f9)
- Codecademy, Introduction to objects, Make Your Own Method [Link to Gist](https://gist.github.com/d359e223c38ab1882a038ff209da15f3)
- Codecademy, Introduction to objects, More Kinds of Methods [Link to Gist](https://gist.github.com/9d4d4bd31d951091a4ff3eaf37a7eb87)
- Codecademy, Introduction to objects, The Object Constructor
 [Link to Gist](https://gist.github.com/3b4b68115bc47008be48ac8c96770f87)
- Codecademy, Introduction to objects, Custom Constructors [Link to Gist](https://gist.github.com/ff6e6f7bd1dc87f8eabea25278810ab3)
- Codecademy, Introduction to objects, Try it Out! [Link to Gist](https://gist.github.com/2bd8e9d60ebff590e243ce6e48f05646)
- Codecademy, Introduction to objects, More Options [Link to Gist](https://gist.github.com/a029a43c9ae570355d07d9a03dda04b5)
- Codecademy, Introduction to objects, Constructors With Methods [Link to Gist](https://gist.github.com/e5ef1ad2fc99e5929753266851e54695)
- Codecademy, Introduction to objects, Constructors in Review [Link to Gist](https://gist.github.com/1485dccb775d7c5967105d9de52d8e98)

#### Day 12
- Codecademy, Introduction to objects, Arrays of Objects [Link to Gist](https://gist.github.com/321c5e9a67dc9cd493458296a9816b4c)
- Codecademy, Introduction to objects, Loop the loop [Link to Gist](https://gist.github.com/229d46127da3d815cea9baf270322c0a)

#### Day 13
- Codecademy, Introduction to objects, Passing Objects into Functions
 [Link to Gist](https://gist.github.com/a3cfa90aa425dcbdc805e70f9e21886f)
- Codecademy, Introduction to objects, Try it Out! [Link to Gist](https://gist.github.com/37a45ddb179abc59867302efc80ac8c8)
- Codecademy, Introduction to objects, What Are Objects For? [Link to Gist](https://gist.github.com/08b2dba9b55d57265048a23809953882)
- Codecademy, Introduction to objects, Properties
 [Link to Gist](https://gist.github.com/144d09dcfee8b3c03e6bc99d5cabafcc)
- Codecademy, Introduction to objects, Customizing Constructors [Link to Gist](https://gist.github.com/95b30c2f3e9ce25e424ea172b5d7a975)
- Codecademy, Introduction to objects, Methods [Link to Gist](https://gist.github.com/0e669d3215b776f4edce2ca43c6bbc1b)

#### Day 14
- Codecademy, Building an Address Book, Digitizing People
 [Link to Gist](https://gist.github.com/dcbe2282f27a4f9d7ab57ac03ba84365)
- Codecademy, Building an Address Book, More People
 [Link to Gist](https://gist.github.com/922865d3869b9487ddb78de84c046321)
- Codecademy, Building an Address Book, Displaying People
 [Link to Gist](https://gist.github.com/3830135cea5aa1cf9ecedee6720bf62c)
- Codecademy, Building an Address Book, Listing Everybody
 [Link to Gist](https://gist.github.com/3b5e64585a06120780172b512874e3b0)
- Codecademy, Building an Address Book, Finding that Special Someone
 [Link to Gist](https://gist.github.com/367dd3d050b07127504f367220ca0d97)
- Codecademy, Building an Address Book, We Made a Friend! [Link to Gist](https://gist.github.com/c77a1847d46d1049ff4aef19031e5b0a)

#### Day 15
Codecademy, Introduction to Objects II:
- An Objective Review [Link to Gist](https://gist.github.com/7f43d9493ca6785ec28776e89a4915bb)
- Fun with Functions [Link to Gist](https://gist.github.com/3956cb2576e357889c7d30e533fdcf06)
- Literally Speaking [Link to Gist](https://gist.github.com/23ba0c93227cc7adc8d1d3251b0690e7)
- Can I See Your References? [Link to Gist](https://gist.github.com/8755c2772021e9b92785c557a67b2647)
- Who's in Your Bracket? [Link to Gist](https://gist.github.com/c81b55bda29406600a8a430430fd23e4)
- I.D., Please [Link to Gist](https://gist.github.com/7f158c828500249a43ac2c1871d27328)
- Know Thyself [Link to Gist](https://gist.github.com/8a363e9dd9e44b639976d557f541a418)
- Dressed to Impress [Link to Gist](https://gist.github.com/18fc8c5da2728e3849ea20a3ef4072bd)
- Getting IN-timate [Link to Gist](https://gist.github.com/fcd885f1848152d0761fc1c8c2de0aef)
- List ALL the Properties! [Link to Gist](https://gist.github.com/b6fc8cc6013876fb8e75a8a22b4fd60f)

#### Day 16
Codecademy, Introduction to Objects II:
- Class is in Session [Link to Gist](https://gist.github.com/8e50a9a6b0d00f31e2cf9d5f3a3bbc71)
- Teach Snoopy[Link to Gist](https://gist.github.com/858ef8d26b32c9de4b6a6890354beb67)
- How do Classes Help Us? [Link to Gist](https://gist.github.com/223cceef6c76839a319b53a71b56eaf3)
- Prototype to the Rescue [Link to Gist](https://gist.github.com/d5d64b07b69d0438a020dc22e9c4eb1e)
- Prototype Practice [Link to Gist](https://gist.github.com/cb917fbfe8d3540da177ca8dd992fe1d)
- It's All in the Genes [Link to Gist](https://gist.github.com/aead803fe7051df3094007c7ea5be800)
- Marching Penguins [Link to Gist](https://gist.github.com/e169a759624915675ee7eefdef9ab599)
- DRY Penguins [Link to Gist](https://gist.github.com/2aabcda51ba1c9241c7cf95c96d4bf45)
- Black (and White) Penguin Magic [Link to Gist](https://gist.github.com/b080f5b0a020ea4be10c61465571ff31)

#### Day 17
Codecademy, Introduction to Objects II:
- Penguins, Properties, and the Prototype [Link to Gist](https://gist.github.com/ccd5005a80ec69144db09e4a09f1c58a)
- Up the Food-I-mean-Prototype Chain [Link to Gist](https://gist.github.com/58fd5b2852a42c86bad8f00b7aba4e42)
- Open to the Public [Link to Gist](https://gist.github.com/9500ab5a56af74926ce99d55f1c28f78)
- Private Variables [Link to Gist](https://gist.github.com/2acda2836895f5c3e40b069fd0dd02f8)
- Accessing Private Variables [Link to Gist](https://gist.github.com/73221d2d6861f6b62a4840183d665e51)
- Private Methods [Link to Gist](https://gist.github.com/7e17e8216a71d642b05fbc49128aa395)
- Passing Arguments [Link to Gist](https://gist.github.com/cce18ea59481f4ec1913e2c9c222ab05)
- Looks For-In To Me [Link to Gist](https://gist.github.com/7f55f2d3e5bc004c814dd4915dc92c8e)
- Hello? Yes, This is Dog [Link to Gist](https://gist.github.com/6db4ece95d3e1f2e0179fc36b36b6abd)
- So Meta I Can't Take It! [Link to Gist](https://gist.github.com/6d60522432796df2d5290ec230f354a3)
- Private Eye [Link to Gist](https://gist.github.com/c918a3560975a6ef3e84afc292f282e6)

#### Day 17
Codecademy jQuery - Modifying HTML Elements [Link to Gist](https://gist.github.com/codecademydev/0c72d33e5b1e5daf7a6062cfd64147ca)
