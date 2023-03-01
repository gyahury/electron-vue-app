<template>
    <v-card>
        <v-layout>
            <v-navigation-drawer floating permanent elevation="3" color="rgb(255, 255, 255)">
                <v-list nav>
                    <v-list-item prepend-icon="mdi-swap-horizontal" title="파일이름 출력" value="filenamelist"></v-list-item>
                    <v-list-item prepend-icon="mdi-swap-horizontal" title="To CSV" value="tocsv"></v-list-item>
                    <v-list-item prepend-icon="mdi-swap-horizontal" title="To XLSX" value="toxlsx"></v-list-item>
                    <v-list-item prepend-icon="mdi-swap-horizontal" title="To JSON" value="tojson"></v-list-item>
                    <v-list-item prepend-icon="mdi-swap-horizontal" title="이미지 해상도 출력" value="imageresol"></v-list-item>
                    <v-list-item prepend-icon="mdi-swap-horizontal" title="이미지 해상도 변경" value="chgimgresol"></v-list-item>
                    <v-list-item prepend-icon="mdi-swap-horizontal" title="폴더 내 파일 분리" value="sepfile"></v-list-item>
                    <v-list-item prepend-icon="mdi-swap-horizontal" title="폴더/파일명 일괄 변경" value="chafilename"></v-list-item>
                </v-list>
            </v-navigation-drawer>
            <v-main style="height: 550px;"></v-main>
        </v-layout>
    </v-card>
</template>

<style>
.v-list-item--nav .v-list-item-title{
    color: rgb(95, 94, 94); 
}
.v-list{
    margin-top: 10px;
}
</style>