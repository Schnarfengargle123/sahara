<template>
    <Navbar />
    <CardItems />
</template>

<script>
import Navbar from '../components/Navbar';
import CardItems from '../components/CardItems';

export default {
    name: "Dashboard",
    components: {
        Navbar,
        CardItems
    }
}
</script>