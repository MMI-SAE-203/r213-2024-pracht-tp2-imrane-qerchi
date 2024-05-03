<script setup lang="ts">
import { MaisonRecord } from '@/types';
import MaisonCard from '@/components/MaisonCard.vue';

const maisonsListe: MaisonRecord[] = [
  {
    "adresse": "10 rue du Château , Montbéliard 25400",
    "collectionId": "a66ilxpssp4hwsy",
    "collectionName": "maison",
    "created": "2024-04-12 12:51:53.584Z",
    "favori": true,
    "id": "4rtqi6a9vzboe67",
    "image": "maisons_chateau_tUY8PbTdPg.jpg",
    "nbChambres": 10,
    "nbSdb": 6,
    "nomMaison": "Château de la Vallée ",
    "prix": 2000000,
    "surface": 1000,
    "updated": "2024-04-12 12:51:53.584Z"
  },
  {
    "adresse": "20 rue des Artisans , Strasbourg 67000",
    "collectionId": "a66ilxpssp4hwsy",
    "collectionName": "maison",
    "created": "2024-04-12 12:54:58.265Z",
    "favori": false,
    "id": "ru3mi2reuoz1de4",
    "image": "293_maison_en_bois_ds_les_vieux_quartiers_d_istanbul_YsbxRVMyDw.jpg",
    "nbChambres": 3,
    "nbSdb": 2,
    "nomMaison": "Maison du Vieux Quartier",
    "prix": 400000,
    "surface": 150,
    "updated": "2024-04-12 12:54:58.265Z"
  },
  {
    "adresse": "30 chemin du Soleil , Nice 06000",
    "collectionId": "a66ilxpssp4hwsy",
    "collectionName": "maison",
    "created": "2024-04-12 12:57:38.895Z",
    "favori": true,
    "id": "wf2n90ucs21ak3i",
    "image": "villa_nice_3BzDdaeWo3.jpg",
    "nbChambres": 8,
    "nbSdb": 5,
    "nomMaison": "Villa Azur",
    "prix": 1200000,
    "surface": 600,
    "updated": "2024-04-12 12:57:38.895Z"
  },
  {
    "adresse": "40 Chemin de la Forêt , Saint-Gobain 02410",
    "collectionId": "a66ilxpssp4hwsy",
    "collectionName": "maison",
    "created": "2024-04-12 12:59:48.901Z",
    "favori": false,
    "id": "aak463rzld53aia",
    "image": "ootravaux_construction_chalet_prix_1000x667_9ZAKk8UVzX.jpg",
    "nbChambres": 4,
    "nbSdb": 3,
    "nomMaison": "Chalet du Bois ",
    "prix": 300000,
    "surface": 200,
    "updated": "2024-04-12 12:59:48.901Z"
  },
  {
    "adresse": "50 Boulevard du Rivage , Bidart 64000",
    "collectionId": "a66ilxpssp4hwsy",
    "collectionName": "maison",
    "created": "2024-04-12 13:02:56.478Z",
    "favori": true,
    "id": "5hxcasl8373zqi5",
    "image": "villa_panorama_bidart_piscine_proche_plages_et_centre_exterior_DB2V7FSgsX.jpg",
    "nbChambres": 7,
    "nbSdb": 5,
    "nomMaison": "Villa Panorama",
    "prix": 3000000,
    "surface": 500,
    "updated": "2024-04-12 13:02:56.478Z"
  }
]
</script>

<template>
  <div>
    <MaisonCard/>  
  <h1 class="text-2xl">Bonjour monde !</h1>
  </div>
</template>