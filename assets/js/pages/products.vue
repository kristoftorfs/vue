<template>
    <div class="container-fluid">
        <div class="row">
            <aside class="col-xs-12 col-3">
                <sidebar />
            </aside>
            <div class="col-xs-12 col-9">
                <catalog />
            </div>
        </div>
    </div>
</template>

<script>
import Sidebar from '@/components/sidebar';
import Catalog from '@/components/catalog';

export default {
    name: 'Products',
    components: {
        Sidebar, Catalog,
    },
};
</script>
