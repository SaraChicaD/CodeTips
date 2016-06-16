const formatString = (text, maxLength = 10) => {
  if (text.length < maxLength) {
    return text;
  } else {
    const start = text.substr(0, maxLength - 1 - 3);
    const end = text.substr(text.length - 3);
    return `${start}…${end}`;
  }
};