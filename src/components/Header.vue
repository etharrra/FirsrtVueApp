<template>
    <div>
        <b-nav tabs>
            <b-nav-item disabled>Dare Quiz</b-nav-item>
            <b-nav-item disabled>Count: {{ numCorrect }}/{{ numTotal }}</b-nav-item>
        </b-nav>
    </div>
</template>

<script>
export default {
    props : [
        'numCorrect',
        'numTotal'
    ]
}
</script>