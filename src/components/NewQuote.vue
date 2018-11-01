<template>
    <div class="row">
        <form>
            <div class="col-sm-8 col-sm-offset-2 col-xs-12 col-md-6 col-md-offset-3">
                <label>Quote</label>
                <textarea rows="3" class="form-control" v-model="quote"></textarea>
            </div>
        </form>
    </div>
</template>

<script>
export default {
    data: function() {
        return {
            quote: ''
        };
    }
}
</script>

<style>
    
</style>