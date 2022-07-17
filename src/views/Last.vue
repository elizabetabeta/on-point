<template>
 
  <div class="about">

    <h1 style="color:#d96459;">Pronađite odgovaraući termin i rezervirajte ga!</h1>
<br>
<br>
<p> Ovdje vrlo jednostavno možete pronaći odgovarajući termin za traženu uslugu uz samo par klikova.Prilikom registracije ostvaljate nam svoj broj telefona i email adresu a mi vama datum i vrijeme termina te adresu salona.
</p>

<v-row>
  <v-col>
<p>Odaberite termin</p>
    <datetime format="MM/DD/YYYY" width="300px" v-model="val"></datetime> <br>
<v-btn>
Izaberi ovaj datum
  </v-btn>
  </v-col>
  <v-col>
    <img src="https://us.123rf.com/450wm/nobilior/nobilior1312/nobilior131200055/24679154-pretty-woman-with-a-cosmetic-brush-white-background.jpg?ver=6" height="300px" />
  </v-col>
</v-row>

  </div>
  
</template>


<script>
import datetime from 'vuejs-datetimepicker';
 
export default {
    components: { datetime }
};
</script> 
