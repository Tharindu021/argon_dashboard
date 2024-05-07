<template>
    <DashboardLayout>
        <template #header>
            <Cards />
        </template>
        <template #content>

            <div class="row">
                <Chart />
                <Performance />
            </div>

            <div class="row">
                <TeamMembers />
                <ToDoList />
                <ProgressTrack />
            </div>

            <div class="row">
                <ActivityFeed />
                <LightTable />
            </div>

            <div class="row">
                <PageVisits />
                <SocialTrafic />
            </div>

        </template>
    </DashboardLayout>
</template>

<script setup>
    import Cards from '../../Components/Dashboard/Cards.vue';
    import DashboardLayout from '../../Layouts/DashboardLayout.vue';
    import Chart from '../../Components/Dashboard/Chart.vue';
    import Performance from '../../Components/Dashboard/Performance.vue'
    import TeamMembers from '../../Components/Dashboard/TeamMembers.vue';
    import ToDoList from '../../Components/Dashboard/ToDoList.vue';
    import ProgressTrack from '../../Components/Dashboard/ProgressTrack.vue';
    import ActivityFeed from '../../Components/Dashboard/ActivityFeed.vue';
    import LightTable from '../../Components/Dashboard/LightTable.vue';
    import PageVisits from '../../Components/Dashboard/PageVisits.vue';
    import SocialTrafic from '../../Components/Dashboard/SocialTrafic.vue';
</script>

<style lang="scss">
</style>
