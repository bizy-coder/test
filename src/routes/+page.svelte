<script lang="ts">
	import { xml } from 'cheerio';
	import Scrollbar from './Scrollbar.svelte';
	import Table from './Table.svelte';
	import { problems } from './data-store';
	import { scoreboard_info } from './data-store';

	// let contestURL = '';
</script>

<Scrollbar />
<Table scoreboard_info={$scoreboard_info} problems={$problems} />
