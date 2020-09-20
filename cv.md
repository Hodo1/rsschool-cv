# My CV

### Vladyslav Rudkovskyi

### Contact info:
* [Number](0668488032)
* [Telegtam](https://t.me/HoDo_HoDo)
* [E-mail](barabashkavq2000@gmail.com)
### Summary
***I will become a professional Front-End developer.***

**I will do whatever it takes to achieve this goal. In the IT field, I must always learning new. This is a rapidly developing field, and in order to improve the quality of my work, you always need to get new knowledge.**
### Skils
* HTML
* CSS
* SASS
* Flexbox
* Git
### Code example:
    const binarySearch = (data, target, start, end) => {
      if(end < 1) return data[0];
      const middle = Math.floor((start + (end - start)/2);
      if (target == data[middle].svgX) return data[middle];
      if (end — 1 === start) return Math.abs(data[start].svgX — target) > Math.abs(data[end].svgX — target) ? data[end] : data[start]; 
      if (target > data[middle].svgX) return binarySearch(data,target,middle,end);
      if (target < data[middle].svgX) return binarySearch(data,target,start,middle);
    }
    let closestPoint = binarySearch(data,target, 0, data.length-1)   
