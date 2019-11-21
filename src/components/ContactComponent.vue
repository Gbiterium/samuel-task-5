<template>
    <div class="contact">
    <div class="container">
    <div class="row">
    <div class="col-md-8 col-md-offset-2">
    <div class="panel panel-default">
    <div class="panel-heading">CONTACT US</div>
    <div class="panel-body">
    <form class="form">
            <div class="form-group">
                <label>Name</label>
                <input type="text" class="form-control" id="inputName" placeholder="Enter your full name" />
            </div>
            <div class="form-group">
                <label>Email</label>
                <input type="text" class="form-control" id="inputEmail" placeholder="Enter your Email" />
            </div>
            <div class="form-group">
                <label>Message</label>
                <textarea type="text" class="form-control" id="inputMessage" rows="5" placeholder="Your Message here"></textarea>
            </div>
            <button type="submit" class="btn btn-default btn-lg" style="font-size:18px; border-radius:10px; background:black; color:white">Submit</button>
        </form>
    </div>
    </div>
    </div>
    </div>
    </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.form-control{
    font-size: 18px;
}
</style>
