<template>
  <section class="cart">
    <div class="container">
      <div class="row">
        <div class="col-xl-12">
          <div class="cart_table_box">
            <table class="cart_table">
              <thead class="cart_table_head">
              <tr>
                <th>Item</th>
                <th></th>
                <th>Price</th>
                <th>Quantity</th>
                <th>Total</th>
                <th>Remove</th>
              </tr>
              </thead>
              <tbody>
              <tr>
                <td colspan="2">
                  <div class="colum_box">
                    <div class="prod_thum">
                      <a href="#"><img src="/assets/images/shop/cart_product_img-1.jpg"
                                       alt=""></a>
                    </div>
                    <div class="title">
                      <h3 class="prod-title">Basket full of vegetables</h3>
                    </div>
                  </div>
                </td>
                <td class="pro_price">$9.99</td>
                <td class="pro_qty">
                  <div class="product-quantity-box">
                    <div class="input-box">
                      <input class="quantity-spinner" type="number" value="1"
                             name="quantity">
                    </div>
                  </div>
                </td>
                <td class="pro_sub_total">$9.99</td>
                <td>
                  <div class="pro_remove">
                    <i class="fas fa-times"></i>
                  </div>
                </td>
              </tr>
              <tr>
                <td colspan="2">
                  <div class="colum_box">
                    <div class="prod_thum">
                      <a href="#"><img src="/assets/images/shop/cart_product_img-2.jpg" alt=""></a>
                    </div>
                    <div class="title">
                      <h3 class="prod-title">Oranges</h3>
                    </div>
                  </div>
                </td>
                <td class="pro_price">$9.99</td>
                <td class="pro_qty">
                  <div class="product-quantity-box">
                    <div class="input-box">
                      <input class="quantity-spinner" type="number" value="1" name="quantity">
                    </div>
                  </div>
                </td>
                <td class="pro_sub_total">$9.99</td>
                <td>
                  <div class="pro_remove">
                    <i class="fas fa-times"></i>
                  </div>
                </td>
              </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
      <div class="row cart_apply_coupon_box">
        <div class="col-xl-6">
          <div class="apply_coupon">
            <div class="apply_coupon_input_box">
              <input type="text" name="coupon-code" value="" placeholder="Enter Coupon Code">
            </div>
            <div class="apply-coupon-button">
              <button class="thm-btn" type="submit">Apply Coupon</button>
            </div>
          </div>
        </div>
        <div class="col-xl-6">
          <ul class="total_box list-unstyled">
            <li><span>Subtotal</span>$19.98 USD</li>
            <li><span>Shipping Cost</span>$0.00 USD</li>
            <li><span>Total</span>$19.98 USD</li>
          </ul>
        </div>
      </div>
      <div class="row">
        <div class="col-xl-12">
          <div class="button_box">
            <button class="thm-btn update_btn" type="button">Update</button>
            <button class="thm-btn checkout_btn" type="button">Checkout</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "Cart"
    }
</script>

<style scoped>

</style>
