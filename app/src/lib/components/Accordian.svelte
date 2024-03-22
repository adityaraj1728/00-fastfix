<script lang="ts">
    import { Accordion, AccordionItem } from '@skeletonlabs/skeleton';
</script>

<Accordion class="card p-4 text-token">
    <AccordionItem open>
        <svelte:fragment slot="lead"><i>🔥</i></svelte:fragment>
        <svelte:fragment slot="summary">
            <p class="font-bold">
                What is the total cost of migrating data to QuickBooks Online?
            </p>
        </svelte:fragment>
        <svelte:fragment slot="content">
            <p>
                The total cost of data migration to QuickBooks depends on the amount of data you want to migrate. To minimize the cost, migrate only the balances.    
            </p>
        </svelte:fragment>
    </AccordionItem>
    <AccordionItem>
        <svelte:fragment slot="lead">🔥</svelte:fragment>
        <svelte:fragment slot="summary">How much time does QuickBooks migration process take?</svelte:fragment>
        <svelte:fragment slot="content">It may take up to 2 weeks to transfer your data to QuickBooks Online, set up custom integrations, customize the app experience, and train your team on the new accounting solution.</svelte:fragment>
    </AccordionItem>
    <AccordionItem>
        <svelte:fragment slot="lead"><i>🔥</i></svelte:fragment>
        <svelte:fragment slot="summary">How will you keep data for multiple entities separate in QuickBooks Online?</svelte:fragment>
        <svelte:fragment slot="content">Unlike NetSuite and Sage Intacct, QuickBooks Online uses classes to differentiate among divisions and departments. So apart from customizing your chart of accounts, we'll also map the entities to unique classes so that you can view and analyze data for each separately.</svelte:fragment>
    </AccordionItem>
</Accordion>