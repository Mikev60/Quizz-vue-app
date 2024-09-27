<template>
    <div class="result">
        <div class="title">You got sample result {{ correctAnswers }}!</div>
        <div class="desc">
            Enter a short description here about the result.
        </div>
    </div>
</template>

<script>
export default {
    name: 'Result',
    props: ["correctAnswers"]
}
</script>

<style></style>