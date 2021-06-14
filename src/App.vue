<template>
  <div class="p-fluid" style="margin-bottom:10px;">
    <div class="p-field">
      <label>I will change on save</label>
      <InputText type="text" placeholder="I will change on save" />
    </div>
  </div>
  <hr />
  <TabView>
    <TabPanel header="I won't changee">
      <div class="p-fluid">
        <div class="p-field">
          <label>I won't changee</label>
          <InputText type="text" placeholder="I won't change" />
        </div>
      </div>
    </TabPanel>
    <TabPanel header="I won't change">
      <div class="p-fluid">
        <div class="p-field">
          <label>I won't change</label>
          <Dropdown optionLabel="name" placeholder="I won't change" />
        </div>
      </div>
    </TabPanel>
  </TabView>
  <hr />
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
.p-field > label {
  display: inline-block;
  margin-bottom: 0.5rem;
}
</style>
