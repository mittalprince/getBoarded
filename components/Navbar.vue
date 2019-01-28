<template>
    <div>
        <b-navbar toggleable="md" type="dark" variant="info">

        <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
        <b-navbar-brand href="#">getBoarded</b-navbar-brand>
        <b-collapse is-nav id="nav_collapse">

            <b-navbar-nav>
            <b-nav-item href="#">Find Jobs</b-nav-item>
            <b-nav-item href="#">Resume</b-nav-item>
            <b-nav-item href="#">Employess</b-nav-item>
            <b-nav-item href="#">Analytics</b-nav-item>
            </b-navbar-nav>

            <!-- Right aligned nav items -->
            <b-navbar-nav class="ml-auto">

            <b-nav-item href="#">Contact</b-nav-item>
            <b-nav-item-dropdown text="User" right>
                <b-dropdown-item href="#">Login</b-dropdown-item>
                <b-dropdown-item href="#">SignUp</b-dropdown-item>
            </b-nav-item-dropdown>
            </b-navbar-nav>

        </b-collapse>
        </b-navbar>

        <div id="header"> 
            
            <nav class="nav">
                <nuxt-link class="nav-link active" to="/">Active</nuxt-link>
                <nuxt-link class="nav-link" to="/jobs">Jobs</nuxt-link>
                <nuxt-link class="nav-link" to="/candidates">Candidates</nuxt-link>
                <nuxt-link class="nav-link" to="/career">Career Page</nuxt-link>

                <form class="form-inline my-2 my-lg-0 ml-auto">
                    <input class="form-control mr-lg-2" type="search" placeholder="Search Candidates.." aria-label="Search">
                    <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Post a Job</button>
                </form>
            </nav>
    
        </div>
    </div>
</template>

<style>


#header{
    background-color:white;
    padding-top:10px;
    padding-bottom: 10px;
    font-size: 20px;
}
form{
    margin-right: 10px;
}
</style>