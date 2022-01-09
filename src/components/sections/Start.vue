<template>
    <section>
        <div class="container">
            <h2>Get started now.</h2>
            <button>Create your account</button>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Start'
}
</script>

<style lang="scss" scoped>

    section {
        background-color: #0041be;
        padding: 60px 0;
        text-align: center;

        h2 {
            color: white;
            margin-bottom: 20px;
        }

        button {
            border-radius: 6px;
            border: none;
            padding: 10px;
            background-color: white;
            color: #0078ff;
            box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
            transition: transform 0.5s;

            &:hover {
                transform: scale(1.1);
            }
        }
    }

</style>