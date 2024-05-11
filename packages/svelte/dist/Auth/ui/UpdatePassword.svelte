<script>import Auth from '../Auth.svelte';
export let supabaseClient;
export let redirectTo = undefined;
export let showLinks = false;
export let appearance = {};
export let theme = 'default';
export let passwordLimit = false;
export let localization = {};
</script>

<Auth
	view="update_password"
	{showLinks}
	{supabaseClient}
	{redirectTo}
	{appearance}
	{theme}
	{passwordLimit}
	{localization}
/>
