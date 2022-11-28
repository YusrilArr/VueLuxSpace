.<template>
<div class="mx-2 ">
    <div class="text-md-center mt-5 mb-5">
        <img src="../assets/img/logo.png">
    </div>

    <div class="d-flex flex-row justify-content-around mb-5">

        <div class="d-flex flex-column">
            <h4>Overview</h4>
            <a href="" style="text-decoration:none; color:black;">Shipping</a>
                        <a href="" style="text-decoration:none; color:black;">Refund</a>
                        <a href="" style="text-decoration:none; color:black;">Promotion</a>
                    </div>
    
                    <div class="d-flex flex-column">
                        <h4>Company</h4>
                        <a href="" style="text-decoration:none; color:black;">About</a>
                        <a href="" style="text-decoration:none; color:black;">Career</a>
                        <a href="" style="text-decoration:none; color:black;">Contact Us</a>
                    </div>
    
                    <div class="d-flex flex-column">
                        <h4>Explore</h4>
                        <a href="" style="text-decoration:none; color:black;">Term & Condition</a>
                        <a href="" style="text-decoration:none; color:black;">Privacy Policy</a>
                        <a href="" style="text-decoration:none; color:black;">For Developers</a>
                    </div>

                    <nav class="navbar navbar-light d-flex flex-column">
                        <form class="container-fluid">
                            <h4>Special Letters</h4>
                          <div class="input-group">
                              <input type="email" class="form-control" placeholder="Your Email Address" id="subs" name="email" required>
                              <button type="submit" class="input-group-text" id="btnAlert" style="background-color:red;">
                                <img src="../assets/img/tele-icon.png">
                              </button>
                          </div>
                        </form>
                      </nav>


                </div>




            </div>
</template>

<script>
export default {
    name: "FooterComp",

};
</script>

<style>

</style>