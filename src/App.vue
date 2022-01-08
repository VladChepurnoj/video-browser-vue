<template>
    <div>
       <SearchBar @termChange="onTermChange" ></SearchBar>
    </div>
</template>

<script>
import SearchBar from './components/SearchBar'
// const API_KEY= 'AIzaSyAI2D9WBlr3Bz_S1MR5oO9kRJJuv7wN1co'


export default {
    name:'App',
    components:{
        SearchBar
    },
    methods:{
        onTermChange(searchTerm){
            console.log(searchTerm)
        }
    }
}
</script>
  