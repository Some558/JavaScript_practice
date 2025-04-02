### querySelectorALLで取得できる要素

// IDで要素を選択（単一要素でも複数形式で取得）
const elementById = document.querySelectorAll('#myId');

// クラスで要素を選択
const elementsByClass = document.querySelectorAll('.myClass');

// タグ名で要素を選択
const allParagraphs = document.querySelectorAll('p');

// 属性で要素を選択
const inputElements = document.querySelectorAll('[type="text"]');

// 複合セレクタの例
// myClass クラスを持つ div 内の全ての p 要素
const nestedParagraphs = document.querySelectorAll('div.myClass p');

// ID が container である要素内の全ての li 要素
const listItems = document.querySelectorAll('#container li');

// 擬似クラスも使用可能
const firstChildren = document.querySelectorAll('li:first-child');