<script>
    import {messages} from './utils'
</script>

<ul>
{#each messages as message}
    <li>{message}</li>
{/each}
</ul>