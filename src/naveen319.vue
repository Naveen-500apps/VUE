<template>
    <div>
                  NaVeEn </div>
<h2>message:{{message}}
</h2>
    <h2>name:{{name}}
    </h2>
    <h2>number:{{number}}
    </h2>
    <h2>workingcompany:{{workingcompany}}
    </h2>
</template>
<script>

export default {
name:"NaVeen",
props:{

message : String,
name : String,
number : Number,
workingcompany: String
}
}
</script>
