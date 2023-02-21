<!-- <template>
    <div style="display: flex; flex-direction: column-reverse;">
        <v-toolbar style="border-radius: 15px; height: 100px;">
            <v-toolbar-title class="text-grey" style="border-radius: 50px; text-align: right;">
                Title
            </v-toolbar-title>
            <v-text-field style="border-radius: 5px;" placeholder="Search for category, name, keyword, etc."
                prepend-inner-icon="mdi-magnify"></v-text-field>
        </v-toolbar>
        <h1 style="text-align: right;">Assessment and Certification</h1>
    </div>
    <v-main
        style="--v-layout-left:56px; --v-layout-right:0px;/* --v-layout-top:128px; */ --v-layout-bottom:550px;"></v-main>
</template>

<style>
.v-field.v-field--prepended.v-field--variant-filled.v-theme--light {
    border-radius: 15px;
    margin-top: 55px;
}
</style> -->


<!-- <template>
    <v-container fluid>
        <v-row class="d-flex align-center justify-center">
            <v-col cols="12" md="9" lg="8">
                <h1 class="header">Assessment and Certification</h1>
            </v-col>
        </v-row>
        <v-row class="d-flex align-center justify-center">
            <v-col cols="12" md="9" lg="8">
                <v-toolbar dense style="border-radius: 15px; height: 150px;">
                    <v-toolbar-title class="text-black; text-bold" style="border-radius: 50px; font-weight: bold;">
                        What are you looking for?
                    </v-toolbar-title>
                    <v-text-field flat solo style="border-radius: 5px;"
                        placeholder="Search for category, name, keyword, etc."
                        prepend-inner-icon="mdi-magnify"></v-text-field>
                </v-toolbar>
            </v-col>
        </v-row>
        <v-row class="d-flex align-center justify-center">
            <v-col cols="12" md="9" lg="8">
                <v-main style="--v-layout-bottom: 550px;"></v-main>
            </v-col>
        </v-row>
    </v-container>
</template>
  
<style>
.header {
    text-align: left;
}

.v-field.v-field--prepended.v-field--variant-filled.v-theme--light {
    border-radius: 15px;
    margin-top: 50px;
}

@media only screen and (min-width: 768px) {
    .v-field.v-field--prepended.v-field--variant-filled.v-theme--light {
        margin-top: 70px;
    }
}

@media only screen and (min-width: 1024px) {
    .v-field.v-field--prepended.v-field--variant-filled.v-theme--light {
        margin-top: 100px;
    }
}
</style>
   -->

<!-- <template>
    <v-container fluid>
        <h1 class="header">Assessment and Certification</h1>
        <v-spacer></v-spacer>
        <v-toolbar style="border-radius: 15px; height: 150px; align-items: center;">
            <v-toolbar-title class="text-black; text-bold" style="border-radius: 50px; font-weight: bold; flex: 1;">
                What are you looking for?
            </v-toolbar-title>
            <v-text-field flat solo style="border-radius: 5px; flex: 1;"
                placeholder="Search for category, name, keyword, etc." prepend-inner-icon="mdi-magnify"></v-text-field>
        </v-toolbar>
        <v-main
            style="--v-layout-left:56px; --v-layout-right:0px;/* --v-layout-top:128px; */ --v-layout-bottom:550px;"></v-main>
    </v-container>
</template>
<style>
.v-field.v-field--prepended.v-field--variant-filled.v-theme--light {
    border-radius: 15px;
    margin-top: 150px;
}

.v-input__control {
    display: flex;
    grid-area: control;
}

.header {
    margin-left: 50px;
}
</style> -->


<template  style="background-color: #F7F7FB;">
    <v-container class="px-16">
        <h1 class="px-9">Assessment and Certification</h1>
        <v-container style="border-radius: 15px; background-color: white;" class="px-10">

            <v-row no-gutters>
                <v-col>
                    <v-toolbar-title class="text-black; text-bold" style="font-weight: bold;">What are
                        you looking for?</v-toolbar-title>
                </v-col>
            </v-row>

            <v-row no-gutters>
                <v-col>
                    <v-text-field solo prepend-inner-icon="mdi-magnify" style=" flex: 1;"
                        placeholder="Search for category, name, keyword, etc."></v-text-field>
                </v-col>

            </v-row>
        </v-container>


    </v-container>
</template>

<style>
.v-field__input {
    border-radius: 1000px;
}

.v-main {
    flex: 1 0 auto;
    max-width: 100%;
    transition: 0.2s cubic-bezier(0.4, 0, 0.2, 1);
    padding-left: var(--v-layout-left);
    padding-right: var(--v-layout-right);
    padding-top: var(--v-layout-top);
    padding-bottom: var(--v-layout-bottom);
    background-color: #F7F7FB;
}

.v-field.v-field--prepended.v-field--variant-filled.v-theme--light {
    border-radius: 15px;
}
</style>