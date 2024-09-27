<template>
  <div class="flex flex-col min-h-screen">
    <main class="flex-grow">
      <div class="max-w-screen-xl mx-auto p-4 my-20">
        <form>
          <div class="mb-5">
            <FloatLabel>
              <InputText id="username" />
              <label for="username">Username</label>
            </FloatLabel>
          </div>
          <Button label="Submit" />
        </form>
      </div>
    </main>
  </div>
</template>
