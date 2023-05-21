function indexOfIgnoreCase(str1, str2) {
  let str1Lower = str1.toLowerCase();
  let str2Lower = str2.toLowerCase();
  return str1Lower.indexOf(str2Lower);
}
