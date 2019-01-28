<template> 

    <b-container id="candidates">
        <b-row>
            <b-col cols="6" md="3">
                <h5> Candidates Filters </h5>
                <b-row id="location"> 
                    <b-form-group label="Locations">
                        <b-form-checkbox-group stacked v-model="selected" name="flavour2" :options="options">
                        </b-form-checkbox-group>
                    </b-form-group>
                </b-row>
                <b-row id="education">
                    <b-form-group label="Locations">
                        <b-form-checkbox-group stacked v-model="selected" name="flavour2" :options="options">
                        </b-form-checkbox-group>
                    </b-form-group>
                </b-row>
                <b-row id="current_position">
                    <b-form-group label="Locations">
                        <b-form-checkbox-group stacked v-model="selected" name="flavour2" :options="options">
                        </b-form-checkbox-group>
                    </b-form-group>
                </b-row>

                <hr>

                <h5> Application Questions </h5>
                <b-row id="writing">
                    <b-form-group label="Locations">
                        <b-form-checkbox-group stacked v-model="selected" name="flavour2" :options="options">
                        </b-form-checkbox-group>
                    </b-form-group>
                </b-row>
                <b-row id="social_media"> 
                    <b-form-group label="Locations">
                        <b-form-checkbox-group stacked v-model="selected" name="flavour2" :options="options">
                        </b-form-checkbox-group>
                    </b-form-group>
                </b-row>
                <b-row id="language">
                    <b-form-group label="Locations">
                        <b-form-checkbox-group stacked v-model="selected" name="flavour2" :options="options">
                        </b-form-checkbox-group>
                    </b-form-group>
                </b-row>

            </b-col>

            <b-col cols="12" md="8">

                <b-row>
                    <h5 style="margin-left: 12px;"> Candidates for Content Writer - Noida, Uttar Pradesh Job Details </h5>
                    <!-- <p> <br> </p> -->
                    <b-col cols="4">
                        <b-form-group label="Job Titles:">
                        <b-form-select v-model="selected" :options="option" class="mb-3" />
                        </b-form-group>
                    </b-col>
                    <b-col cols="4">
                         <b-form-group label="Job Titles:">
                        <b-form-select v-model="selected" :options="option" class="mb-3" />
                        </b-form-group>
                    </b-col>
                    <b-col>
                        <b-form-group label="Interest Level">
                        <b-form-checkbox-group stacked v-model="selected" name="flavour2" :options="Options">
                        </b-form-checkbox-group>
                    </b-form-group>
                    </b-col>
                    <b-col>
                        <b-form-group label="Read Status">
                        <b-form-checkbox-group stacked v-model="selected" name="flavour2" :options="Options">
                        </b-form-checkbox-group>
                    </b-form-group>
                    </b-col>
                
                </b-row>
                
                <hr> 

                <b-row id="profiles">
                    <b-card-group deck class="mb-3">
                        <b-card title="Prince Mittal"
                                img-src="https://picsum.photos/600/300/?image=25"
                                img-alt="Image"
                                img-top
                                tag="article"
                                style="max-width: 20rem;"
                                class="mb-2">
                            <p class="card-text">
                            New Delhi, Delhi <br>
                            M.Tech
                            </p>
                            <b-button href="#" variant="primary">Show Profileß</b-button>
                        </b-card>
                        <b-card title="Prince Mittal"
                                img-src="https://picsum.photos/600/300/?image=25"
                                img-alt="Image"
                                img-top
                                tag="article"
                                style="max-width: 20rem;"
                                class="mb-2">
                            <p class="card-text">
                            New Delhi, Delhi <br>
                            M.Tech
                            </p>
                            <b-button href="#" variant="primary">Show Profileß</b-button>
                        </b-card>
                        <b-card title="Prince Mittal"
                                img-src="https://picsum.photos/600/300/?image=25"
                                img-alt="Image"
                                img-top
                                tag="article"
                                style="max-width: 20rem;"
                                class="mb-2">
                            <p class="card-text">
                            New Delhi, Delhi <br>
                            M.Tech
                            </p>
                            <b-button href="#" variant="primary">Show Profileß</b-button>
                        </b-card>
                    </b-card-group>
                    <b-card-group deck class="mb-3">
                        <b-card title="Prince Mittal"
                                img-src="https://picsum.photos/600/300/?image=25"
                                img-alt="Image"
                                img-top
                                tag="article"
                                style="max-width: 20rem;"
                                class="mb-2">
                            <p class="card-text">
                            New Delhi, Delhi <br>
                            M.Tech
                            </p>
                            <b-button href="#" variant="primary">Show Profileß</b-button>
                        </b-card>
                        <b-card title="Prince Mittal"
                                img-src="https://picsum.photos/600/300/?image=25"
                                img-alt="Image"
                                img-top
                                tag="article"
                                style="max-width: 20rem;"
                                class="mb-2">
                            <p class="card-text">
                            New Delhi, Delhi <br>
                            M.Tech
                            </p>
                            <b-button href="#" variant="primary">Show Profileß</b-button>
                        </b-card>
                        <b-card title="Prince Mittal"
                                img-src="https://picsum.photos/600/300/?image=25"
                                img-alt="Image"
                                img-top
                                tag="article"
                                style="max-width: 20rem;"
                                class="mb-2">
                            <p class="card-text">
                            New Delhi, Delhi <br>
                            M.Tech
                            </p>
                            <b-button href="#" variant="primary">Show Profileß</b-button>
                        </b-card>
                    </b-card-group>                    
                    
                </b-row>
            </b-col>

            <hr>

        </b-row>

        
    </b-container>

</template>

<script>
export default {
  data () {
    return {
      selected: [], // Must be an array reference!
      options: [
        {text: 'New Delhi', value: 'new delhi'},
        {text: 'Delhi', value: 'delhi'},
        {text: 'Noida', value: 'noida'},
        {text: 'Gurgoan', value: 'gurgoan'}
      ],
      Options: [
        {text: 'Yes', value: 'yes'},
        {text: 'Maybe', value: 'maybe'}
      ],
      option: [
        { value: null, text: 'Please select an option' },
        { value: 'a', text: 'This is First option' },
        { value: 'b', text: 'Selected Option' },
        { value: {'C': '3PO'}, text: 'This is an option with object value' },
        { value: 'd', text: 'This one is disabled', disabled: true }
      ]
    }
  }
}
</script>

<style>

body{
    background-color: #F5F5F5;
}
.container{
    background-color: white;
    margin-top: 20px;
    margin-bottom: 20px; 
    padding-top: 20px;
}
#location, #education, #current_position, #language, #social_media, #writing{
    margin-left: 8px;
}
#profiles{
    padding: 10px;
}

</style>