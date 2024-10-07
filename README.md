const a = (...elements) => {
    let sum = 0; 
    for (let element of elements) {
        sum += Number(element); 
    }
    let result = sum / elements.length;
    return result;
}

export default a;


