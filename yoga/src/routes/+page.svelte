<div class="formBox">
    <div class="info">
        <h1>Please enter your credit card details below to access my premium yoga course.</h1>
        <h3>Or don't. I don't care. It's seven seconds...</h3>
    </div>
    <div class="name">
        <label for="cardHolder">Name on card:</label>
        <input type="text" name="cardHolder"/>
    </div>
    <div class="number">
        <label for="cardNumber">Card Number:</label>
        <input type="number" name="cardNumber"/>
    </div>
    <div class="date">
        <label for="expiryDate">Expires:</label>
        <input type="month" name="expiryDate"/>
        <label for="cvc">CVC:</label>
        <input type="number" name="cvc"/>
    </div>
    <div class="sub">
        <button><a href="/course">Pay now</a></button>
    </div>
</div>

<style>

    .formBox {
        margin: auto;
        width: 50vw;
        height: 50vh;
        text-align: center;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        row-gap: 10px;
    }
</style>
