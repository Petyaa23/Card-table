<template>
    <h1 class="text-lg text-center font-bold m-5">Cars-table</h1>
    <div class="">
        <button class="bg-gray-500 hover:bg-gray-700 text-white font-bold py-2 px-4 rounded-full">
            Add Exel file
        </button>
    </div>

    <table class="rounded-t-lg m-5 w-5/6 mx-auto bg-gray-800 text-gray-200">
        <tr class="text-left border-b border-gray-300">
            <th class="px-4 py-3">Name</th>
            <th class="px-4 py-3">Model</th>
            <th class="px-4 py-3">Color</th>
            <th class="px-4 py-3">Year</th>
            <th class="px-4 py-3">Price</th>
        </tr>
        <tr class="bg-gray-700 border-b border-gray-600">
            <td class="px-4 py-3">Volkswagen</td>
            <td class="px-4 py-3">Golf-7</td>
            <td class="px-4 py-3">Green</td>
            <td class="px-4 py-3">2020</td>
            <td class="px-4 py-3">5000$</td>
        </tr>
        <tr class="bg-gray-700 border-b border-gray-600">
            <td class="px-4 py-3">BMW</td>
            <td class="px-4 py-3">E60</td>
            <td class="px-4 py-3">Black</td>
            <td class="px-4 py-3">2021</td>
            <td class="px-4 py-3">8000$</td>
        </tr>
        <tr class="bg-gray-700 border-b border-gray-600">
            <td class="px-4 py-3">Mercedes-Benz</td>
            <td class="px-4 py-3">A 35 Sedan</td>
            <td class="px-4 py-3">Red</td>
            <td class="px-4 py-3">2022</td>
            <td class="px-4 py-3">9000$</td>
        </tr>
    </table>
</template>

<script>
export default {
    name: "Dashboard"
}
</script>

