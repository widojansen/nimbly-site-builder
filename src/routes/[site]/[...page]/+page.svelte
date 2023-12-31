<script>
  import { PrimoPage } from 'builderwj'

  export let data
</script>

<PrimoPage
  page={{
    ...data.page,
    sections: data.sections,
  }}
/>
