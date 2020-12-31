<template>
<div class="admin-pages">
    <PageTitle icon="fa fa-cogs" main="Administração do Sistema" sub="Cadastros & cia" />
    <div class="admin-pages-tabs">
        <b-card no-body>
            <b-tabs card>
                <b-tab title="Artigos" active >
                    <h1>Artigo</h1>
                </b-tab>
                <b-tab title="Categorias"  >
                    <h1>Categoria</h1>
                </b-tab>
            </b-tabs>
        </b-card>
    </div>
</div>
   
</template>

<script>
import PageTitle from '../template/PageTitle'

export default {
    name: 'AdminPages',
    components: {PageTitle}
}
</script>

<style>

</style>