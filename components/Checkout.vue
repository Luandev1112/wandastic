<template>
  <section class="checkout">
    <div class="container">
      <div class="row">
        <div class="col-xl-6 col-lg-6">
          <div class="billing_details">
            <div class="billing_title">
              <p>Returning Customer? <span>Click here to Login</span></p>
              <h2>Billing Details</h2>
            </div>
            <form class="billing_details_form">
              <div class="row">
                <div class="col-xl-12">
                  <div class="billing_input_box">
                    <select name="currency" id="currency" class="selectpicker">
                      <option value="Country">Select a country</option>
                      <option value="Canada">Canada</option>
                      <option value="England">England</option>
                      <option value="Australia">Australia</option>
                      <option value="USA">USA</option>
                    </select>
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-xl-6">
                  <div class="billing_input_box">
                    <input type="text" name="first_name" value="" placeholder="First name"
                           required="">
                  </div>
                </div>
                <div class="col-xl-6">
                  <div class="billing_input_box">
                    <input type="text" name="last_name" value="" placeholder="Last name"
                           required="">
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-xl-12">
                  <div class="billing_input_box">
                    <input type="text" name="company_name" value="" placeholder="Company">
                  </div>
                </div>
                <div class="col-xl-12">
                  <div class="billing_input_box">
                    <input type="text" name="Address" value="" placeholder="Address">
                  </div>
                </div>
                <div class="col-xl-12">
                  <div class="billing_input_box">
                    <input type="text" name="company_name" value=""
                           placeholder="Appartment, Unit, etc. (optional)">
                  </div>
                </div>
                <div class="col-xl-12">
                  <div class="billing_input_box">
                    <input type="text" name="Town/City" value="" placeholder="Town / City"
                           required="">
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-xl-6">
                  <div class="billing_input_box">
                    <input type="text" name="State" value="" placeholder="State" required="">
                  </div>
                </div>
                <div class="col-xl-6">
                  <div class="billing_input_box">
                    <input name="form_zip" type="text" pattern="[0-9]*" placeholder="Zip code">
                  </div>
                </div>
                <div class="col-xl-6">
                  <div class="billing_input_box">
                    <input name="email" type="email" placeholder="Email address">
                  </div>
                </div>
                <div class="col-xl-6">
                  <div class="billing_input_box">
                    <input type="tel" name="form_phone" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}"
                           required="" placeholder="Phone number">
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-xl-12">
                  <div class="checkbox">
                    <label>
                      <input type="checkbox" name="ship-same-address">
                      <span>Create an Account?</span>
                    </label>
                  </div>
                </div>
              </div>
            </form>
          </div>
        </div>
        <div class="col-xl-6 col-lg-6">
          <div class="billing_details ship_different_address">
            <div class="billing_title ship_different_address_title">
              <h2>Ship to a different address</h2>
            </div>
            <form class="billing_details_form ship_different_address_form">
              <div class="row">
                <div class="col-xl-12">
                  <div class="billing_input_box">
                    <select name="country" id="country" class="selectpicker">
                      <option value="Country">Select a country</option>
                      <option value="Canada">Canada</option>
                      <option value="England">England</option>
                      <option value="Australia">Australia</option>
                      <option value="USA">USA</option>
                    </select>
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-xl-6">
                  <div class="billing_input_box">
                    <input type="text" name="first_name" value="" placeholder="First name"
                           required="">
                  </div>
                </div>
                <div class="col-xl-6">
                  <div class="billing_input_box">
                    <input type="text" name="last_name" value="" placeholder="Last name"
                           required="">
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-xl-12">
                  <div class="billing_input_box">
                    <input type="text" name="company_name" value="" placeholder="Company">
                  </div>
                </div>
                <div class="col-xl-12">
                  <div class="billing_input_box">
                    <input type="text" name="Address" value="" placeholder="Address">
                  </div>
                </div>
                <div class="col-xl-12">
                  <div class="billing_input_box">
                    <input type="text" name="company_name" value=""
                           placeholder="Appartment, Unit, etc. (optional)">
                  </div>
                </div>
                <div class="col-xl-12">
                  <div class="billing_input_box">
                    <input type="text" name="Town/City" value="" placeholder="Town / City"
                           required="">
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-xl-6">
                  <div class="billing_input_box">
                    <input type="text" name="State" value="" placeholder="State" required="">
                  </div>
                </div>
                <div class="col-xl-6">
                  <div class="billing_input_box">
                    <input name="form_zip" type="text" pattern="[0-9]*" placeholder="Zip code">
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-xl-12">
                  <div class="ship_different_input">
                                            <textarea
                                              placeholder="Notes about your order, e.g special note for delivery"
                                              name="form_order_notes"></textarea>
                  </div>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
      <div class="your_order">
        <h2>Your Order</h2>
        <div class="row">
          <div class="col-xl-6 col-lg-6">
            <div class="order_table_box">
              <table class="order_table_detail">
                <thead class="order_table_head">
                <tr>
                  <th>Product</th>
                  <th class="text-right">Price</th>
                </tr>
                </thead>
                <tbody>
                <tr>
                  <td class="pro__title">Vagetables Pack</td>
                  <td class="pro__price">$9.99 USD</td>
                </tr>
                <tr>
                  <td class="pro__title">Subtotal</td>
                  <td class="pro__price">$9.99 USD</td>
                </tr>
                <tr>
                  <td class="pro__title">Shipping</td>
                  <td class="pro__price">$0.00 USD</td>
                </tr>
                <tr>
                  <td class="pro__title">Total</td>
                  <td class="pro__price">$19.98 USD</td>
                </tr>
                </tbody>
              </table>
            </div>
          </div>
          <div class="col-xl-6 col-lg-6">
            <div class="payments_part">
              <div class="direct">
                <div class="checkbox">
                  <label>
                    <input name="pay-us" type="radio">
                    <span>Direct Bank Transfer</span>
                  </label>
                </div>
                <div class="payments_part_text">
                  <p>Make your payment directly into our bank account. Please use your Order ID as
                    the payment reference. Your order wont be shipped until the funds have
                    cleared in our account.</p>
                </div>
              </div>
              <div class="paypal_payment">
                <div class="checkbox">
                  <label>
                    <input name="pay-us" type="radio">
                    <span>Paypal Payment</span>
                    <i class="paypal_card"><img src="/assets/images/shop/paypal-card.jpg"
                                                alt=""></i>
                  </label>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-xl-12">
                <div class="place_order_btn">
                  <a href="#" class="thm-btn">Place Your Order</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "Checkout"
    }
</script>

<style scoped>

</style>
