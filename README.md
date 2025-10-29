const destroyer = (arr, ...arg) => {
  let newArr = arr.filter((elmt) => !arg.includes(elmt));
  return newArr;
}
