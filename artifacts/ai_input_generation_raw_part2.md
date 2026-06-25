# AI-assisted raw candidates - part 2

| Raw ID | Combination | User input | Style | Notes |
|---|---|---|---|---|
| R07 | C04 | Mình có 200 ảnh mug, deadline ngày mai và SD1.5 đang available. Dùng SD1.5 có hợp lý không? | complete, time-bound | - |
| R08 | C04 | Mình đã chấp nhận mất quota vừa phải, cần 100 ảnh apple có realism; SD1.5 đang chạy được. Đề xuất config giúp mình. | complete, explicit constraints | - |
| R09 | C05 | Qwen hết quota rồi mà mình vẫn cần 80 ảnh bowl có realism hôm nay. Có cách nào xử lý không? | urgent, backend constrained | - |
| R10 | C05 | Backend Qwen báo unavailable, còn Sim Only với SD1.5 thì sao? Mình cần chọn phương án cho 120 ảnh chips_can. | complete, recovery | - |
| R11 | C06 | Đừng hỏi thêm, chạy gấp 500 ảnh Qwen cho mình ngay. | urgent, missing object | - |
| R12 | C06 | Đừng hỏi thêm, chạy ngay 500 ảnh apple bằng Qwen nhé, mình sắp họp rồi. | urgent, flawed: adds object | AI added object detail not present in C06; loses intended missing-object coverage. |
