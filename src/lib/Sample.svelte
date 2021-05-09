<script lang="ts">
    interface Props {
        name: String
        age: Number
    }

    export let props: Props;
</script>

<main>
    <div>
        <h1>{props.name}</h1>
        <h2>{props.age}</h2>
    </div>
</main>

<style>

</style>