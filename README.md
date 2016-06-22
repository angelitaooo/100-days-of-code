# 100-days-of-code

### Day 1
- Manipulating Complex Objects [link to Freecodecamp](https://www.freecodecamp.com/challenges/Manipulating%20Complex%20Objects?solution=%0Avar%20myMusic%20%3D%20%5B%0A%20%20%7B%0A%20%20%20%20%22artist%22%3A%20%22Billy%20Joel%22%2C%0A%20%20%20%20%22title%22%3A%20%22Piano%20Man%22%2C%0A%20%20%20%20%22release_year%22%3A%201973%2C%0A%20%20%20%20%22formats%22%3A%20%5B%20%0A%20%20%20%20%20%20%22CS%22%2C%20%0A%20%20%20%20%20%20%228T%22%2C%20%0A%20%20%20%20%20%20%22LP%22%20%5D%2C%0A%20%20%20%20%22gold%22%3A%20true%0A%20%20%7D%2C%0A%20%20%0A%20%7B%0A%20%20%20%20%22artist%22%3A%20%22coldplay%22%2C%0A%20%20%20%20%22title%22%3A%20%22viva%20la%20vida%22%2C%0A%20%20%20%20%22release_year%22%3A%202009%2C%0A%20%20%20%20%22formats%22%3A%20%5B%0A%20%20%20%20%20%20%22cd%22%2C%0A%20%20%20%20%20%20%22dvd%22%2C%0A%20%20%20%20%20%20%22lp%22%0A%20%20%20%20%5D%0A%20%20%7D%0A%20%20%2F%2F%20Add%20record%20here%0A%5D%3B%0A%0A)
- Accessing Nested Objects [link to Freecodecamp](https://www.freecodecamp.com/challenges/Accessing%20Nested%20Objects?solution=%0A%2F%2F%20Setup%0Avar%20myStorage%20%3D%20%7B%0A%20%20%22car%22%3A%20%7B%0A%20%20%20%20%22inside%22%3A%20%7B%0A%20%20%20%20%20%20%22glove%20box%22%3A%20%22maps%22%2C%0A%20%20%20%20%20%20%22passenger%20seat%22%3A%20%22crumbs%22%0A%20%20%20%20%20%7D%2C%0A%20%20%20%20%22outside%22%3A%20%7B%0A%20%20%20%20%20%20%22trunk%22%3A%20%22jack%22%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line%0A%0Avar%20gloveBoxContents%20%3D%20myStorage.car.inside%5B%22glove%20box%22%5D%3B%20%2F%2F%20Change%20this%20line%0A%0A)
- Accessing Nested Arrays [link to Freecodecamp](https://www.freecodecamp.com/challenges/Accessing%20Nested%20Arrays?solution=%0A%2F%2F%20Setup%0Avar%20myPlants%20%3D%20%5B%0A%20%20%7B%20%0A%20%20%20%20type%3A%20%22flowers%22%2C%0A%20%20%20%20list%3A%20%5B%0A%20%20%20%20%20%20%22rose%22%2C%0A%20%20%20%20%20%20%22tulip%22%2C%0A%20%20%20%20%20%20%22dandelion%22%0A%20%20%20%20%5D%0A%20%20%7D%2C%0A%20%20%7B%0A%20%20%20%20type%3A%20%22trees%22%2C%0A%20%20%20%20list%3A%20%5B%0A%20%20%20%20%20%20%22fir%22%2C%0A%20%20%20%20%20%20%22pine%22%2C%0A%20%20%20%20%20%20%22birch%22%0A%20%20%20%20%5D%0A%20%20%7D%20%20%0A%5D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line%0A%0Avar%20secondTree%20%3D%20myPlants%5B1%5D.list%5B1%5D%3B%20%2F%2F%20Change%20this%20line%0A%0A)

### Day2
- Iterate with JavaScript For [Link](https://www.freecodecamp.com/challenges/Iterate%20with%20JavaScript%20For%20Loops?solution=%0A%2F%2F%20Example%0Avar%20ourArray%20%3D%20%5B%5D%3B%0A%0Afor%20(var%20i%20%3D%200%3B%20i%20%3C%205%3B%20i%2B%2B)%20%7B%0A%20%20ourArray.push(i)%3B%0A%7D%0A%0A%2F%2F%20Setup%0Avar%20myArray%20%3D%20%5B%5D%3B%0A%0Afor%20(var%20i%20%3D%201%3B%20i%20%3C%206%3B%20i%2B%2B)%20%7B%0A%20%20myArray.push(i)%3B%0A%7D%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A%0A)
- Iterate Odd Numbers With a For Loop	[Link](https://www.freecodecamp.com/challenges/Iterate%20Odd%20Numbers%20With%20a%20For%20Loop?solution=%0A%2F%2F%20Example%0Avar%20ourArray%20%3D%20%5B%5D%3B%0A%0Afor%20(var%20i%20%3D%200%3B%20i%20%3C%2010%3B%20i%20%2B%3D%202)%20%7B%0A%20%20ourArray.push(i)%3B%0A%7D%0A%0A%2F%2F%20Setup%0Avar%20myArray%20%3D%20%5B%5D%3B%0A%20%20for%20(var%20i%20%3D%201%3B%20i%20%3C10%3B%20i%2B%3D2)%7B%0A%20%20%20%20myArray.push(i)%3B%0A%20%20%7D%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A%0A)
- Count Backwards With a For Loop	[Link](https://www.freecodecamp.com/challenges/Count%20Backwards%20With%20a%20For%20Loop?solution=%0A%2F%2F%20Example%0Avar%20ourArray%20%3D%20%5B%5D%3B%0A%0Afor%20(var%20i%20%3D%2010%3B%20i%20%3E%200%3B%20i%20-%3D%202)%20%7B%0A%20%20ourArray.push(i)%3B%0A%7D%0A%0A%2F%2F%20Setup%0Avar%20myArray%20%3D%20%5B%5D%3B%0A%20%20for%20(var%20i%20%3D%209%3B%20i%20%3E%200%3B%20i%20-%3D%202)%7B%0A%20%20%20%20myArray.push(i)%3B%0A%20%20%7D%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A)
- Iterate Through an Array with a For Loop	[Link](https://www.freecodecamp.com/challenges/Iterate%20Through%20an%20Array%20with%20a%20For%20Loop?solution=%0A%2F%2F%20Example%0Avar%20ourArr%20%3D%20%5B%209%2C%2010%2C%2011%2C%2012%5D%3B%0Avar%20ourTotal%20%3D%200%3B%0A%0Afor%20(var%20i%20%3D%200%3B%20i%20%3C%20ourArr.length%3B%20i%2B%2B)%20%7B%0A%20%20ourTotal%20%2B%3D%20ourArr%5Bi%5D%3B%0A%7D%0A%0A%2F%2F%20Setup%0Avar%20myArr%20%3D%20%5B%202%2C%203%2C%204%2C%205%2C%206%5D%3B%0Avar%20total%20%3D%200%3B%0Afor%20(var%20i%20%3D%200%3B%20i%20%3C%20myArr.length%3B%20i%2B%2B)%7B%0A%20%20total%20%2B%3D%20myArr%5Bi%5D%3B%0A%7D%0A%2F%2F%20Only%20change%20code%20below%20this%20line%0A%0A%0A)
- Nesting For Loops	[Link](https://www.freecodecamp.com/challenges/Nesting%20For%20Loops?solution=%0Afunction%20multiplyAll(arr)%20%7B%0A%20%20var%20product%20%3D%201%3B%0A%20%20%2F%2F%20Only%20change%20code%20below%20this%20line%0A%20%20for%20(var%20i%20%3D%200%3B%20i%20%3C%20arr.length%3B%20i%2B%2B)%7B%0A%20%20%20%20%20%20for%20(var%20j%20%3D%200%3B%20j%20%3C%20arr%5Bi%5D.length%3B%20j%2B%2B)%20%7B%0A%20%20%20%20%20%20%20%20console.log(arr%5Bi%5D%5Bj%5D)%3B%0A%20%20%20%20%20%20%20%20product%20%3D%20product%20*%20arr%5Bi%5D%5Bj%5D%3B%0A%20%20%20%20%20%20%7D%0A%20%20%7D%0A%20%20%2F%2F%20Only%20change%20code%20above%20this%20line%0A%20%20return%20product%3B%0A%7D%0A%0A%2F%2F%20Modify%20values%20below%20to%20test%20your%20code%0AmultiplyAll(%5B%5B1%2C2%5D%2C%5B3%2C4%5D%2C%5B5%2C6%2C7%5D%5D)%3B%0A%0A)
- Iterate with JavaScript While Loops	[Link](https://www.freecodecamp.com/challenges/Iterate%20with%20JavaScript%20While%20Loops?solution=%0A%2F%2F%20Setup%0Avar%20myArray%20%3D%20%5B%5D%3B%0Avar%20i%20%3D%200%3B%0Awhile(%20i%20%3C%205)%20%7B%0A%20%20myArray.push(i)%3B%0A%20%20i%2B%2B%3B%0A%7D%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A%0A)
- Generate Random Fractions with JavaScript	[Link](https://www.freecodecamp.com/challenges/Generate%20Random%20Fractions%20with%20JavaScript?solution=%0Afunction%20randomFraction()%20%7B%0A%0A%20%20%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A%20%20return%20Math.random()%3B%0A%0A%20%20%2F%2F%20Only%20change%20code%20above%20this%20line.%0A%7D%0A)
- Generate Random Whole Numbers with JavaScript [Link](https://www.freecodecamp.com/challenges/Generate%20Random%20Whole%20Numbers%20with%20JavaScript?solution=%0Avar%20randomNumberBetween0and19%20%3D%20Math.floor(Math.random()%20*%2010)%3B%0A%0Afunction%20randomWholeNum()%20%7B%0A%0A%20%20%2F%2F%20Only%20change%20code%20below%20this%20line.%0A%0A%20%20return%20Math.floor(Math.random())%3B%0A%7D%0A)
