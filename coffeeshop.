document.addEventListener('DOMContentLoaded', function() {
    // Get all order buttons
    const orderButtons = document.querySelectorAll('.order-btn');

    // Function to handle the order
    function orderItem(event) {
        const itemName = event.target.getAttribute('data-name');
        const itemPrice = parseFloat(event.target.getAttribute('data-price'));

        // Display a confirmation message
        alert(`Thank You For Ordering!!!                                                    
        You have ordered ${itemName} for Rs/- ${itemPrice}`);
    }

    // Add click event listener to each order button
    orderButtons.forEach(button => {
        button.addEventListener('click', orderItem);
    });
})
