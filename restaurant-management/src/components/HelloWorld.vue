<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-card>
          <v-layout>
            <v-navigation-drawer
              expand-on-hover
              rail
            >
              <v-list>
                <v-list-item
                  prepend-avatar="https://randomuser.me/api/portraits/men/85.jpg"
                  title="Shetcor"
                  subtitle="conrad15@gmailcom"
                ></v-list-item>
              </v-list>

              <v-divider></v-divider>

              <v-list density="compact" nav>
                <v-list-item prepend-icon="mdi-hamburger" title="Dashboard" value="dashboard"></v-list-item>
                <v-list-item prepend-icon="mdi-account-multiple" title="Chefs" value="chefs"></v-list-item>
                <v-list-item prepend-icon="mdi-star" title="Meals" value="meals"></v-list-item>
                <v-list-item prepend-icon="mdi-gift" title="Orders" value="orders"></v-list-item>
              </v-list>
            </v-navigation-drawer>

            <v-main style="height: 300px;"></v-main>
            <v-row class="app-title">
            </v-row>
            <v-row>
              <v-col cols="12">
                <v-img :src="require('../assets/logo.svg')" class="my-3" contain height="50" />
              <h3>Restaurant Management App</h3>
              </v-col>
              <v-col cols="12" class="button-adds">
                <v-btn prepend-icon="mdi-account-plus" variant="tonal" color="info"> Add chef</v-btn>&nbsp;
                <v-btn prepend-icon="mdi-basket-plus" variant="tonal" color="default"> Add meal</v-btn>&nbsp;
                <v-btn prepend-icon="mdi-gift" variant="tonal" color="error"> Add order</v-btn>
              </v-col>
              <v-col cols="12">
                <h4 class="chefs-table">Chefs</h4>
                <v-table fixed-header border="1">
                  <thead>
                    <tr class="table-heading">
                      <td>First name</td>
                      <td>Last name</td>
                      <td>ID Number</td>
                      <td>Gender</td>
                      <td>Phone number</td>
                      <td>Address</td>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td>Conrad</td>
                      <td>Tazvivinga</td>
                      <td>54 127113 S12</td>
                      <td>Male</td>
                      <td>+263 784 680 934</td>
                      <td>46 Bannister Road, Braeside</td>
                    </tr>
                    <tr>
                      <td>Conrad</td>
                      <td>Tazvivinga</td>
                      <td>54 127113 S12</td>
                      <td>Male</td>
                      <td>+263 784 680 934</td>
                      <td>46 Bannister Road, Braeside</td>
                    </tr>
                    <tr>
                      <td>Conrad</td>
                      <td>Tazvivinga</td>
                      <td>54 127113 S12</td>
                      <td>Male</td>
                      <td>+263 784 680 934</td>
                      <td>46 Bannister Road, Braeside</td>
                    </tr>
                    <tr>
                      <td>Conrad</td>
                      <td>Tazvivinga</td>
                      <td>54 127113 S12</td>
                      <td>Male</td>
                      <td>+263 784 680 934</td>
                      <td>46 Bannister Road, Braeside</td>
                    </tr>
                    <tr>
                      <td>Conrad</td>
                      <td>Tazvivinga</td>
                      <td>54 127113 S12</td>
                      <td>Male</td>
                      <td>+263 784 680 934</td>
                      <td>46 Bannister Road, Braeside</td>
                    </tr>
                  </tbody>
                </v-table>
              </v-col>
            </v-row>
            
          </v-layout>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>

export default {
  name: 'HelloWorld',
}
</script>

<style>
.text-center{
  font-family: Poppins;
}

.button-adds{
  padding-top: 30px;
}
.table-heading{
  font-weight: 700;
}
.chefs-table{
  color: navy;
}
.app-title{
  padding-top: px;
}
</style>
