<template>
  <div class="home">
    <h1>Home</h1>

    <CustomText class="a1" tag="p"> A1</CustomText>
    <CustomText class="a2" tag="p" size="small"> A2</CustomText>
    <CustomText class="a3" tag="p" size="xsmall"> A3</CustomText>
    <CustomText tag="p" size="xxsmall"> XX</CustomText>
    <IconHome width="60" height="60" />
   

   <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum, eius
        vero. Alias aut blanditiis commodi consectetur eligendi, et minima
        officiis omnis optio pariatur quod quos repudiandae rerum sed tempora
        voluptatibus?
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum, eius
        vero. Alias aut blanditiis commodi consectetur eligendi, et minima
        officiis omnis optio pariatur quod quos repudiandae rerum sed tempora
        voluptatibus?
      </p>
      
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum, eius
        vero. Alias aut blanditiis commodi consectetur eligendi, et minima
        officiis omnis optio pariatur quod quos repudiandae rerum sed tempora
        voluptatibus?
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum, eius
        vero. Alias aut blanditiis commodi consectetur eligendi, et minima
        officiis omnis optio pariatur quod quos repudiandae rerum sed tempora
        voluptatibus?
      </p>

      <div class="sidebar">
        <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum, eius
        vero. Alias aut blanditiis commodi consectetur eligendi, et minima
        officiis omnis optio pariatur quod quos repudiandae rerum sed tempora
        voluptatibus?
      </p>
      
        </div>


     

  </div>
</template>

<script>
import CustomText from '@/components/CustomText'
import IconHome from '../../icons/home.svg'
export default {
  name: 'Home',
  components: {
    CustomText,
    IconHome
  }
}
</script>
<style scoped>
.home {
  max-width: 605px;
  margin-left: auto;
  margin-right: auto;
  @media (--t) {
    max-width: none;
    display: grid;
    grid-template-columns: 1fr 295px;
    grid-gap: 30px;
  }
}
.sidebar {
  display: none;
  @media (--t) {
    display: block;
  }
}
</style>
