
## Lifecycle hooks 👩‍💻 : 

- beforeCreate 
- created  
- beforeMount 
- mounted 
- BeforeUpdated 
- updated 
- beforeUnmount 
- unmounted 


### beforeCreate

#### Usage/Examples

```javascript

<script>
export default {

 beforeCreate() {
    console.log(
    "The vue instance is initialized, and before create hook is called !!"
    );
  }
}
</script>
```

```
output : The vue instance is initialized, and before create hook is called !!  
```

### created

#### Usage/Examples

```javascript

<script>
export default {
    data() {
    return {
      name: "Nadir"
    };
  }, 

 created() {
    console.log(`Created hooks is called : ${this.name}`);
  }
}
</script>
```

```
output : Created hooks is called : Nadir  
```

### beforeMount

#### Usage/Examples

```javascript

<script>
export default {

  beforeMount() {
    console.log("before mount hooked is well called !!");
  }
}
</script>
```

```
output : before mount hooked is well called !!  
```
### mounted

#### Usage/Examples

```javascript

<script>
export default {

 mounted() {
    console.log("mounted is called !!");
  }
}
</script>
```

```
output :mounted is called !! 
```
### beforeUpdate

#### Usage/Examples

```javascript

<script>
export default {

  beforeUpdate() {
    console.log(
      "before updated hook is well called, wich means that changes has been done, and the Virtual DOM has not been re-rendred !!"
    );
  }
}
</script>
```

```
output :before updated hook is well called, wich means that changes has been done, and the Virtual DOM has not been re-rendred !! 
```
### updated

#### Usage/Examples

```javascript

<script>
export default {

updated() {
    console.log(
      "at this point updated hook is called, and Virtual DOM is well re-rendred !!"
    );
  } , 
}
</script>
```

```
output :at this point updated hook is called, and Virtual DOM is well re-rendred !!  
```
### beforeUnmount

#### Usage/Examples

```javascript

<script>
export default {

beforeUnmount(){
    console.log(
        "beforeUnmount is called right before the $el is removed from the DOM "
    )
  }
}
</script>
```

```
output :beforeUnmount is called right before the $el is removed from the DOM
```
### unmounted

#### Usage/Examples

```javascript

<script>
export default {

  unmounted(){
    console.log("Vue instance is unmounted and removed from DOM .")
  }
}
</script>
```

```
output :Vue instance is unmounted and removed from DOM . 
```

## Lifecycle Diagram

![App Screenshot](https://vuejs.org/assets/lifecycle.16e4c08e.png)

## Feedback

If you have any feedback, please reach out to me at :
- 📫 :nadir.inab.dev@gmail.com 
- [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nadirinab/)
