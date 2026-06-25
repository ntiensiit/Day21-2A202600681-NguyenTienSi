# AI-assisted raw candidates - part 3

| Raw ID | Combination | User input | Style | Notes |
|---|---|---|---|---|
| R13 | C07 | Mình muốn tạo data cho cái hộp sữa Ovaltine, chọn class nào cho gần nhất? | natural, unsupported object | - |
| R14 | C07 | Mug với coffee cup cũng là một, tạo class mug luôn được chứ? | ambiguous alias, flawed | AI converted the unsupported-object test into an in-scope alias case. |
| R15 | C08 | Mình cần ảnh photorealistic, miễn phí, không dùng GPU và phải xong trong 2 phút. Chọn workflow nào? | short, conflicting constraints | - |
| R16 | C08 | Dataset phải giống ảnh thật nhất nhưng 0 quota, deadline 5 phút; mình không muốn giảm số lượng ảnh. Có config nào đáp ứng hết không? | long, conflicting constraints | - |
| R17 | C09 | Mai sáng demo, mình cần 500 ảnh SD1.5 cho đủ 7 object nhưng quota còn ít. Có kịp không? | deadline, high-risk | - |
| R18 | C09 | Cần 300 ảnh SD1.5 cho cracker_box trước chiều nay, quota còn 25%. Đừng cho phương án chậm quá. | urgent, high-risk | - |
