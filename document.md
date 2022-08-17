1. HTML
2. CSS
3. Javascript
  3.1. Làm quen với javascript
  3.2. Vòng lặp và input
  3.3. Mảng Array
  - ten_mang.push(ten_bien); //Thêm phần tử vào cuối mảng
  3.4. Regex
  - Tìm kiếm những thứ hợp lệ trong một chuỗi kí tự
    [a-z0-9\_]+@[a-z]+\.[a-z]+
    +: min: 1, max: vô cực
    _: min: 0, max: vô cực
    []: min: 1, max: 1
    {1,10}: min: 1, max: 10 //[a-z]{1,10}
    {1,}: min: 1, max: vô cực
    {10}: min: 10, max: 10
    \: ép nó là ký tự bình thường
    ?: lấy cũng đk mà k lấy cũng đk
    ^: bắt đầu chuỗi //^[a-z] -> chỉ lấy những điều kiện bắt đầu bằng chữ
    $: kết thúc chuỗi
    \w: [a-zA-Z0-9]
    \W: [^a-zA-Z0-9] -> lấy những kí tự còn lại ngoài những cái trên //vd: @!$#%^. ,()_
    \d: [0-9]
    \D: [^0-9]
    .: mọi kí tự
  - check số điện thoại:
    ^(0|\+84)[1-9][0-9]{8,9}$
  - check điểm:
    - điểm từ 0-10
    - sau dấu chấm chỉ có 2 số
    - sau dấu chấm không được chứa số 0 cuối cùng
    - có thể sử dụng dấu chấm hay dấu phẩy đều được
      kq: ^(10|[0-9]([.,][0-9]?[1-9])?)$
  3.5. Validate form
  - sinh 1 HTML bên cạnh thẻ
    class_name.insertAdjacentHTML('afterend', '<span>Không được để trống</span>');
  3.6. DOM & BOM
  - 