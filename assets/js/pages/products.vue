<template>
    <div class="container-fluid">
        <div class="row">
            <aside class="col-xs-12 col-3">
                <catalog />
            </aside>

            <div class="col-xs-12 col-9">
                <sidebar />
            </div>
        </div>
    </div>
</template>

<script>
import Sidebar from '@/components/catalog';
import Catalog from '@/components/sidebar';

export default {
    name: 'Products',
    components: {
        Sidebar,
        Catalog,
    },
};
</script>
