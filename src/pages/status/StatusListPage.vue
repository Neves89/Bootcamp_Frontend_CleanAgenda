<script setup lang="ts">
import { DefaultTemplate } from '@/template'

const itensDaTabela = [
    {
        nome: 'Elephante Africano',
        species: 'Loxodonta africana',
        diet: 'Herbivore',
        habitat: 'Savannah',
    },
    {
        nome: 'Africano',
        species: 'Loxodonta africana',
        diet: 'Herbivore',
        habitat: 'Savannah',
    },
    {
        nome: 'Africano',
        species: 'Loxodonta africana',
        diet: 'Herbivore',
        habitat: 'Savannah',
    },
    {
        nome: 'Africano',
        species: 'Loxodonta africana',
        diet: 'Herbivore',
        habitat: 'Savannah',
    },
    
]
</script>

<template>
    <DefaultTemplate>
        <v-data-table :items="itensDaTabela"></v-data-table>
    </DefaultTemplate>
</template>