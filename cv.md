# Artsemij Spryntsyn

**Tel**: +375292884393, **vk**: [@artik122](https://vk.com/artik122), **mail**: sprincyn@gmail.com.

* My **Goals** may seem trivial to some, but I have them, and I am gradually and confidently moving on my path of self-education.
> *You don't have to be the best, you just have to be better than you were yesterday*
> *Joe Frazier*.

* I study front languages such as ***JavaScript, HTML, and CSS***. I also don't stop there and study the framework in addition ***Vue.js***.

* This code snippet shows the functionality for entering grades in subjects (conditionally school) on **Vue**. Depending on the entered data or data from the server, the number of inputs for entering ratings changes.

```html
<div class="subj " class="input-field col s12">
Number of subjects:
<input type="number" id="inputSubj" min="1" max="50" v-model.number.lazy="lengthEvals" @change="inputCounts" v-focus><br>
<div class="subjects" v-for="(value, index) of lengthEvals">
<input type="number" v-model.number="evals[index]" id="inputValueSubjects" min="1" max="10" @change="getValues" required>
<button type="button" class="numerals btn-floating waves-effect waves-light green" v-for="i in 10" @click="setValue(index, i)">{{i}}</button>
</div>
<div class="mean">Average score in subjects: {{mean}}, value: {{mean*10}}</div>
</div>
```

### Experience
* A year ago, I took a course in JS at **Anderson**. At the moment participating in the training courses **rsschool** JS. I also get information from **Glo Academy** online courses and from the Internet throughout the year. Some works are posted on my [**GitHub**](https://github.com/Flashbuck).

### Education
- Sukhoi State Technical University of Gomel (2020)

### English
* My English level is ***A2*** and it is also written in **my self development list**.
