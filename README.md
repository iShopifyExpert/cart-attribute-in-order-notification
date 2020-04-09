# cart-attribute-in-order-notification


            
            <div class="mess-box"><div class="inner-msg">
              <p class="cart-attribute__field">
                <label for="if-this-is-a-gift-you-can-include-a-message-here">If this is a gift, you can include a message here:</label>
                <textarea id="if-this-is-a-gift-you-can-include-a-message-here" name="attributes[gift-message]">{{ cart.attributes["gift-message"] }}</textarea>
              </p>
            </div>
            <div class="inner-msg">
              <p class="cart-attribute__field">
                <label for="if-you-have-specific-delivery-instructions-please-leave-here">If you have specific delivery instructions, please leave here:</label>
                <textarea id="if-you-have-specific-delivery-instructions-please-leave-here" name="attributes[delivery-instructions]">{{ cart.attributes["gift-message"] }}</textarea>
              </p>
            </div>
          </div>

