<script>
let name = ['John', 'Doe', 'Jane', 'Doe', 'John', 'Smith', 'Jane', 'Smith'];
import {confetti} from '@neoconfetti/svelte';
import {WebGLRenderer} from 'three';
</script>

<div>
    <h1 use:confetti>Assignment 1</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Est, possimus voluptatem asperiores reiciendis modi quasi in necessitatibus numquam perspiciatis quam atque dicta itaque quisquam a deserunt amet labore aliquid officiis.</p>
</div>
<div>
    <h2>Names</h2>
    <ul>
        {#each name as n}
            <li>{n}</li>
        {/each}
    </ul>
</div>
<canvas>

</canvas>

<style>

</style>