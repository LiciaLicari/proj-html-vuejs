<script>
export default {
    name: 'AppFooter',

}
</script>

<template>
   <footer>
        <div class="footer_top d-flex">

            <div class="col">
                <img src="../assets/img/instagram_img1.jpg" alt="">
            </div>
            <div class="col">
                <img src="../assets/img/instagram_img2.jpg" alt="">
            </div>
            <div class="col">
                <img src="../assets/img/instagram_img3.jpg" alt="">
            </div>
            <div class="col">
                <img src="../assets/img/instagram_img4.jpg" alt="">
            </div>
            <div class="col">
                <img src="../assets/img/instagram_img5.jpg" alt="">
            </div>
            <div class="col">
                <img src="../assets/img/instagram_img6.jpg" alt="">
            </div>
            <div class="col">
                <img src="../assets/img/instagram_img7.jpg" alt="">
            </div>
            <div class="col">
                <img src="../assets/img/instagram_img8.jpg" alt="">
            </div>

        </div>

        <div class="footer_mid">
            <div class="container pt-5">
                <div class="row">
                    <div class="col-3">
                        <ul class="list-unstyled">
                            <h6>Bookings</h6>
                            <li>502 New Design Str, 
                                Melbourne, San Francisco, 
                                CA 94110, United States Of 
                                America Australia
                            </li>
                            <li>T: 1123-456-789</li>
                            <li>E-mail: demo@example.com</li>
                            <div>
                                <img src="" alt="">
                                <img src="" alt="">
                                <img src="" alt="">
                                <img src="" alt="">
                            </div>
                        </ul>
                    </div>
                    <div class="col-3">
                        <ul class="list-unstyled">
                            <h6>Information</h6>
                            <li>Product Support</li>
                            <li>Checkout</li>
                            <li>Report Abuse</li>
                            <li>Redeem Voucher</li>
                            <li>Order Status</li>
                        </ul>
                    </div>
                    <div class="col-3">
                        <ul class="list-unstyled">
                            <h6>Support</h6>
                            <li>Policies & Rules</li>
                            <li>Privacy Policy</li>
                            <li>License Policy</li>
                            <li>My account</li>
                            <li>Locality</li>
                        </ul>
                    </div>
                    <div class="col-3">
                        <h6>Newsletter</h6>
                        <form>
                            <div class="mb-3">
                                
                                <input type="email" class="form-control" placeholder="Email" required id="exampleInputEmail1"
                                    aria-describedby="emailHelp">
                            </div>
                            <div class="mb-3">
                            
                                <textarea class="form-control" id="validationTextarea"
                                    placeholder="Message" required></textarea>
                                <div class="invalid-feedback">
                                    Please enter a message in the textarea.
                                </div>
                            </div>
                            <button type="submit" class="btn btn_cstm">Send Message</button>
                        </form>
                    </div>
                    <div class="col"></div>
                </div>
            </div>
        </div>
        <div class="footer_bot">
            <hr>
            <p>2023 All Rights Reserved. Developed By
                <a href="#">TemplateMela</a>
            </p>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

</style>