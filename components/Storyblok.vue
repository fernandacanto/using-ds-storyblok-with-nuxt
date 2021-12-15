<template>
<div style="max-width: 400px">
      <SbFormGroup
      :inline="false"
      description="Optional description for group"
      legend="Group Name"
    >
      <SbTextField placeholder="Placeholder" />
      <SbTextField placeholder="Placeholder" />
    </SbFormGroup>
    <SbFormGroup
      :inline="false"
      description="Optional description for group"
      legend="Group Name"
    >
      <SbTextField label="Label" />
      <SbTextField label="Label" />
    </SbFormGroup>
    <SbFormGroup
      :inline="false"
      description="Optional description for group"
      legend="Group Name"
    >
      <SbSelect
        label="Choose an option"
        :options='[{"label":"Option 1","value":"Option 1"},{"label":"Option 2","value":"Option 2"},{"label":"Option 3","value":"Option 3"}]'
      />
      <SbSelect
        label="Choose an option"
        :options='[{"label":"Option 1","value":"Option 1"},{"label":"Option 2","value":"Option 2"},{"label":"Option 3","value":"Option 3"}]'
      />
    </SbFormGroup>
</div>
</template>

<script>
export default {
    name: "Storyblok"
}
</script>
