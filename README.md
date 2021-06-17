# intro-curriculum-3007
入門コースの3章7節の練習 (ISC License)
'use strict';
/**
 * 17の倍数である場合 true を返す
 * @param {number} num
 */
function isMultipleOfSeventeen(num) {
  return num % 17 === 0;
}

module.exports = {
  isMultipleOfSeventeen
};
