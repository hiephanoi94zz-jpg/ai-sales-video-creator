# Dynamic Fashion Directing — v2.0

## Mục tiêu
Tạo video thời trang 9:16 với người mẫu AI vui tươi, linh hoạt, tự nhiên như người thật: bước chân có nhịp, xoay người, nhún nhảy, tung tăng, cười, khoe trang phục. Tránh người mẫu đứng cứng, chỉ đi thẳng, vẫy tay lặp lại hoặc biểu cảm vô hồn.

## Ba khóa độc lập, không được trộn lẫn
1. **IDENTITY LOCK:** Dùng chính ảnh tham chiếu nhân vật đã duyệt cho TẤT CẢ cảnh; giữ khuôn mặt, kiểu tóc, tỷ lệ cơ thể, độ tuổi thể hiện và phong thái. Không tạo nhân vật mới.
2. **OUTFIT LOCK:** Dùng ảnh trang phục gốc; giữ màu, họa tiết, đường may, cổ áo, tay áo, độ dài, dáng quần/váy, logo, chất liệu nhìn thấy. Nếu có nhiều bộ, lập bảng rõ cảnh nào mặc bộ nào. Không đổi bộ giữa cảnh khi không được yêu cầu. Khi người mẫu quay, phần lưng không nhìn thấy ở ảnh gốc phải tránh tự khẳng định chi tiết chưa biết.
3. **VOICE LOCK:** Một giọng tiếng Việt, chất giọng, tốc độ, cách phát âm và âm lượng nhất quán. Ưu tiên thu/tạo một voiceover liên tục rồi ghép vào timeline; không yêu cầu từng cảnh tự sinh giọng khác nhau.

## Quy tắc đạo diễn chuyển động
- Mỗi cảnh phải có **hành động chính + hành động phụ + biểu cảm + nhịp chuyển động + tương tác trang phục + góc máy**.
- Chuyển động nối tiếp hợp lý: trọng tâm cơ thể đổi theo bước chân, tay vung tự nhiên, vải chuyển động theo cơ thể, tóc phản ứng nhẹ.
- Khuyến khích: bước nhanh 2–3 bước về phía máy, xoay 90–180 độ có kiểm soát, nhún gối theo nhịp, bước ngang vui tươi, quay đầu mỉm cười, chạm nhẹ vạt áo, xoay váy, hai bước nhảy nhỏ, kết thúc bằng pose.
- Hành động phải phù hợp loại trang phục: váy xòe có thể xoay nhẹ để khoe độ rủ; đồ thể thao có thể bước nhún năng động; áo ôm cần tránh động tác làm sai phom; giày cao gót cần tránh nhảy mạnh không tự nhiên.
- Không biến mọi cảnh thành nhảy liên tục: kết hợp đi, xoay, pose, nhún, cười và cận chất liệu.
- Mỗi cảnh 5–8 giây: tối đa 1 hành động chính và 1–2 chuyển động phụ để tránh lỗi cơ thể.
- Chỉ yêu cầu động tác khả thi; nếu video méo chân/tay, giảm độ phức tạp và tạo lại.

## Ví dụ chuỗi 5 cảnh × 8 giây
| Cảnh | Hành động | Biểu cảm | Góc máy | Điểm khoe đồ |
|---|---|---|---|---|
| 1 | Bước nhanh 2–3 bước, dừng bằng pose nghiêng | Cười rạng rỡ, nhìn máy | Toàn thân tracking nhẹ | Tổng thể bộ đồ |
| 2 | Bước ngang 2 nhịp, nhún gối nhẹ, xoay 90 độ | Tinh nghịch | Toàn thân góc 3/4 | Phom và chuyển động vải |
| 3 | Xoay người chậm 180 độ rồi nhìn lại | Tự tin, tự nhiên | Toàn thân, máy đứng ổn định | Dáng trước và góc bên |
| 4 | Hai bước nhảy nhỏ tại chỗ rồi bước lên một nhịp | Vui tươi | Toàn thân, camera dolly nhẹ | Độ thoải mái khi vận động, không khẳng định tính năng |
| 5 | Bước tiến, chạm nhẹ vạt áo hoặc váy, pose kết | Mỉm cười thân thiện | Trung-toàn thân rồi toàn thân | Chi tiết và tổng thể |

Đây chỉ là gợi ý. Tùy ảnh gốc và loại trang phục mà đổi hành động; không lặp máy móc.

## Prompt tiếng Anh: bắt buộc có mô tả động tác cụ thể
"Vertical 9:16, photorealistic full-body fashion commercial. Use the attached approved character image as the exact identity reference in every shot. Use the attached original outfit photo as the exact clothing reference. Preserve face, hairstyle, body proportions, outfit cut, colors, patterns, logos and fabric appearance. The SAME model takes three lively, naturally weighted steps toward camera, swings arms gently in rhythm, gives a bright genuine smile, makes a playful quarter-turn, and ends in a confident relaxed pose. Realistic foot-ground contact, natural balance, subtle fabric sway and hair movement, responsive facial expressions, fluid body mechanics, energetic yet believable pacing. Full body stays visible including feet, smooth subtle camera tracking, clean daylight, natural motion. No face swap, no wardrobe change, no rigid posture, no robotic walking, no repeated identical gestures, no stiff smile, no extra limbs or fingers, no warped clothing, no flicker, no random text."

## Quy tắc lời thoại theo timeline
- Lập bảng: số cảnh, thời lượng clip thực tế, câu thoại, thời gian đọc thử, điểm bắt đầu/kết thúc, khoảng nghỉ.
- Nếu người dùng muốn 5 cảnh × 8 giây, tổng 40 giây; không viết thoại dài hơn thời gian thực tế.
- Đọc thử/TTS để đo thời gian thật; số chữ chỉ là ước tính, không đảm bảo khớp.
- Nếu lời thoại dài: rút ngắn câu hoặc chuyển ý sang cảnh tiếp theo; không cắt mất chữ cuối.
- Nếu lời thoại ngắn: giữ hành động kết tự nhiên hoặc tăng nhịp nghỉ có chủ đích; không thêm câu vô nghĩa.
- Một voiceover liên tục giúp tránh đổi giọng giữa các cảnh; nếu có thoại trực tiếp/lip-sync từng cảnh, cần kiểm tra từng clip riêng.
- Không tự tuyên bố đã đồng bộ âm thanh nếu chưa kiểm tra video/audio thực tế.

## Kiểm tra bắt buộc trước khi bàn giao
- [ ] Cùng một gương mặt qua mọi cảnh.
- [ ] Đúng trang phục gốc; không sai màu, họa tiết, phom, logo.
- [ ] Mỗi cảnh có hành động khác nhau, sinh động và có mục đích khoe đồ.
- [ ] Cử động tay, chân, hông, vai và trọng tâm tự nhiên.
- [ ] Có biểu cảm vui tươi thay đổi hợp lý, không cười cứng.
- [ ] Toàn thân và chân được nhìn thấy ở các cảnh cần khoe bộ đồ.
- [ ] Lời thoại đúng câu, không thiếu từ hoặc bị cắt cuối.
- [ ] Một giọng xuyên suốt, âm lượng đều.
- [ ] Thời gian các cảnh cộng đúng thời lượng yêu cầu.
- [ ] Nếu một cảnh lỗi, chỉ tạo lại cảnh đó bằng đúng hai ảnh tham chiếu ban đầu.

## Giới hạn
Skill cải thiện chỉ dẫn và kiểm soát chất lượng, nhưng không bảo đảm 100% rằng trình tạo video sẽ giữ đúng mặt, trang phục, động tác hoặc lip-sync. Kết quả phải được xem lại và tạo lại cảnh lỗi khi cần.
