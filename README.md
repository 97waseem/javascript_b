# javascript_b
// B. Perform sorting of an array in descending order.
function sortArrayDescending(arr) {
    return arr.sort((a, b) => b - a);
}

const numbers = [5, 2, 9, 1, 5, 7];
const sortedDescending = sortArrayDescending(numbers);
console.log(sortedDescending);
