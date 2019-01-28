<template> 

    <b-container>
        <b-row>
            <b-col>
                <h3> Candidates Filters </h3>
                <b-row>
                    <b-form-group label="Locations">
                        <b-form-checkbox-group stacked v-model="selected" name="flavour2" :options="options">
                        </b-form-checkbox-group>
                    </b-form-group>
                </b-row>
                <b-row>
                    <b-form-group label="Locations">
                        <b-form-checkbox-group stacked v-model="selected" name="flavour2" :options="options">
                        </b-form-checkbox-group>
                    </b-form-group>
                </b-row>
                <b-row>
                    <b-form-group label="Locations">
                        <b-form-checkbox-group stacked v-model="selected" name="flavour2" :options="options">
                        </b-form-checkbox-group>
                    </b-form-group>
                </b-row>

                <hr>

                <h3> Application Questions </h3>
                <b-row>
                    <b-form-group label="Locations">
                        <b-form-checkbox-group stacked v-model="selected" name="flavour2" :options="options">
                        </b-form-checkbox-group>
                    </b-form-group>
                </b-row>
                <b-row>
                    <b-form-group label="Locations">
                        <b-form-checkbox-group stacked v-model="selected" name="flavour2" :options="options">
                        </b-form-checkbox-group>
                    </b-form-group>
                </b-row>

            </b-col>

            <b-col cols="12" md="auto">

                <b-row>
                    <h3> Candidates for Content Writer - Noida, Uttar Pradesh Job Details </h3>

                </b-row>
                <b-row></b-row>
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
}
</style>