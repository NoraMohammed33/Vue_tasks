<template>
    <table class="table table-striped-bordered col-12 text-center">
        <thead>
            <tr>
                <th>ID</th>
                <th>Name</th>
                <th>City</th>
            </tr>
        </thead>
        <tbody>
            <tr v-for="student in students" :key="student.id">
                <td>{{student.id}}</td>
                <td>{{student.name}}</td>
                <td>{{student.city}}</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <th colspan="3">num of student :{{students.length}}</th>
            </tr>
        </tfoot>

    </table>
</template>

<script>
import student from '../student'
export default {
    data:()=>({
        students:student
    })
}
</script>

<style>

</style>