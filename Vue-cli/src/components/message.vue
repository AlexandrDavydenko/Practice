<template>
<div class="message">
<p>Message component - {{message}}</p>
</div>
</template>
<script>
export default {
props: {
message: {
 type: String,
 //required: true
default: 'message'
}
}   
}

</script>
<style lang="scss"scoped>
.message {
text-align: center;
padding: 20px;
}
</style>