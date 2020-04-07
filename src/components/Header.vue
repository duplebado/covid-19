<template>
    <div>
        <div id="navbar_div">
            <b-navbar>

                <b-collapse id="nav-collapse" is-nav>
                  <b-navbar-nav>
                    <b-nav-item href="#" >Home</b-nav-item> <span></span>
                    <b-nav-item href="#" >What is Corona Virus?</b-nav-item><span></span>
                    <b-nav-item href="#" >Symptoms</b-nav-item><span></span>
                    <b-nav-item href="#" >Prevention</b-nav-item><span></span>
                    <b-nav-item href="#" >FAQs</b-nav-item>
                  </b-navbar-nav>

                  <!-- Right aligned nav items -->
                  <b-navbar-nav class="ml-auto">
                    <b-nav-form>
                      <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
                      <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
                    </b-nav-form>

                    <b-nav-item-dropdown text="Lang" right>
                      <b-dropdown-item href="#">EN</b-dropdown-item>
                      <b-dropdown-item href="#">ES</b-dropdown-item>
                      <b-dropdown-item href="#">RU</b-dropdown-item>
                      <b-dropdown-item href="#">FA</b-dropdown-item>
                    </b-nav-item-dropdown>

                  </b-navbar-nav>
                </b-collapse>
            </b-navbar>
        </div>  
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>
#navbar_div{
    background-color: palevioletred;
}
span{
    margin-left: 70px;
}
</style>