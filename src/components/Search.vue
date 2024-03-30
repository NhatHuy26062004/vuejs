<template>
    <div class="search-bar">
      <input v-model.number="minPrice" class="form-control" type="number" placeholder="Giá tối thiểu">
      <input v-model.number="maxPrice" class="form-control" type="number" placeholder="Giá tối đa">
      <input v-model="searchTerm" class="form-control" type="text" placeholder="Tìm kiếm sản phẩm...">
      <button @click="search" class="btn btn-success">Tìm kiếm</button>
    </div>
  </template>
  
  <script>
  export default {
    name:"SearchComponent",
    data() {
      return {
        searchTerm: '',
        minPrice: null,
      maxPrice: null
      };
    },
    methods: {
      search() {
      this.$emit('search', { term: this.searchTerm, minPrice: this.minPrice, maxPrice: this.maxPrice });
    }
    }
  };
  </script>
  
  <style>
  .form-control{
    padding: 10px;
  }
  .search-bar {
    display: flex;
    align-items: center;
    margin-top: 20px;
  }
  
  .search-bar input {
    flex: 1;
    margin-right: 10px; 
  }
  
  .btn-success {
    background-color: #28a745;
    color: #fff;
    border: none; 
    border-radius: 5px;
    padding: 10px 20px; 
    cursor: pointer;
  }
  

  </style>
  