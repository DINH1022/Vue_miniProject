<template>
    <div class="product-info">
        <div class="pricing-header px-3 py-3 pt-md-5 pb-md-4 mx-auto text-center">
            <h2 class="display-4">User Infomation</h2>
            <router-link to="/user">Back</router-link>
        </div>

        <div class="container">
            <form @submit.prevent="save()">
                <div class="form-group row">
                    <label for="inputPassword" class="col-sm-3 col-form-label">Name</label>
                    <div class="col-sm-9">
                        <input type="text" class="form-control" />
                    </div>
                </div>
                <div class="form-group row">
                    <label for="inputPassword" class="col-sm-3 col-form-label">Age</label>
                    <div class="col-sm-9">
                        <input type="text" class="form-control" />
                    </div>
                </div>
                <div class="form-group row">
                    <label for="inputPassword" class="col-sm-3 col-form-label">Email</label>
                    <div class="col-sm-9">
                        <textarea class="form-control" rows="3"></textarea>
                    </div>
                </div>
                <div class="form-group row">
                    <label for="inputPassword" class="col-sm-3 col-form-label"></label>
                    <div class="col-sm-9">
                        <button type="submit" class="btn btn-primary">Save</button> &nbsp;
                        <button type="reset" class="btn btn-danger">Cancel</button>
                    </div>
                </div>
            </form>
        </div>
    </div>
</template>