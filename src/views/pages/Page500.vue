<template>
  <CContainer class="d-flex align-items-center min-vh-100">
    <CRow class="w-100 justify-content-center">
      <CCol md="6">
        <div class="clearfix">
          <h1 class="float-left display-3 mr-4">500</h1>
          <h4 class="pt-3">Ops Você tem um problema está página está fora do ar!</h4>
          <p class="text-muted">Está temporariamente fora do ar.</p>
        </div>
        <CInput
          class="mb-3"
          placeholder="Qual é o seu erro?"
        >
          <template #prepend-content><CIcon name="cil-magnifying-glass"/></template>
          <template #append>
            <CButton color="info">Buscar</CButton>
          </template>
        </CInput>
      </CCol>
    </CRow>
  </CContainer>
</template>

<script>
export default {
  name: 'Page500'
}
</script>
