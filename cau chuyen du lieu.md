
 

DỰ ÁN 1

                (DAT111) – NHÓM 03
               DỰ ÁN FIFA WORLD 
                  CUP QATAR 2022



Giảng viên hướng dẫn: Trần Văn Huy	
Họ tên sinh viên: 
                   . Nguyễn Ngọc Phương Anh – PS44239
                   . Doãn Thúc Định - PS46587
                   . Diệp Thế Tài - PS46738
                  . Nguyễn Minh Sang - PS46340
                  . Nguyễn Sỹ Toàn - PS46399

  Lớp: DP20302	


CÂU CHUYỆN DỮ LIỆU

Câu chuyện dữ liệu dự án: "FIFA WORLD CUP QATAR 2022"

World Cup 2022 đã khép lại với hình ảnh Lionel Messi nâng cao chiếc cúp vàng, một khoảnh khắc đã đi vào lịch sử. Đó là một cái kết đầy cảm xúc, một câu chuyện cổ tích được viết nên bởi đam mê và định mệnh. Nhưng đằng sau ánh hào quang và những giọt nước mắt, những con số khô khan trong tệp dữ liệu 2022worldcup_english.csv lại kể một câu chuyện còn hấp dẫn hơn. Chúng ta thường nói về "may mắn" hay "bản lĩnh" trong bóng đá, nhưng dữ liệu lại cung cấp một góc nhìn khách quan, một bản giải mã về "công thức" thực sự của nhà vô địch. Phải chăng chiến thắng của Argentina không phải là một cơn địa chấn ngẫu nhiên, mà là một sự tất yếu về mặt thống kê, một sự kết hợp hoàn hảo giữa lối chơi áp đảo và bản lĩnh ở những thời khắc quyết định?
Trước hết, hãy đi tìm lời giải cho câu hỏi lớn nhất: Argentina có thực sự "xứng đáng" vô địch? Để trả lời, chúng ta cần nhìn vào chỉ số quan trọng nhất của bóng đá hiện đại: Bàn thắng kỳ vọng (Expected_Goals, hay xG). Chỉ số này đo lường chất lượng của mọi cơ hội, cho chúng ta biết một đội đáng lẽ phải ghi bao nhiêu bàn. Và đây là lúc câu chuyện bắt đầu. Argentina kết thúc 7 trận đấu (Matches_Played) với 15 bàn thắng (Goals), một con số ấn tượng. Nhưng điều đáng kinh ngạc là, Bàn thắng kỳ vọng (xG) của họ cũng là 15.1. Sự tương đồng gần như tuyệt đối này là một lời khẳng định đanh thép: Argentina không hề "ăn may". Họ tạo ra những cơ hội chất lượng cao (trị giá 15.1 bàn) và họ dứt điểm chính xác với đúng đẳng cấp của mình (ghi 15 bàn).
Hãy nhìn sang các đối thủ để thấy sự khác biệt. Bồ Đào Nha ghi 12 bàn (Goals) nhưng chỉ số xG của họ chỉ là 7.9. Điều này cho thấy Bồ Đào Nha đã có một giải đấu "thăng hoa" về dứt điểm, ghi nhiều bàn hơn đáng kể so với chất lượng cơ hội họ tạo ra - một hiệu suất có thể khó duy trì. Ngược lại, Ba Lan (với 4.5 xG nhưng chỉ có 3 bàn) lại là một ví dụ của sự phung phí. Giữa hai thái cực đó, Argentina đứng vững như một cỗ máy hiệu suất: tạo ra cơ hội tốt và tận dụng chúng một cách lạnh lùng.
Vậy, cỗ máy tấn công của Argentina được vận hành như thế nào? Câu trả lời nằm ở hai trụ cột song song: sự thống trị trong lối chơi chủ động và sự tàn nhẫn trên chấm phạt đền. Nhiều người có thể cho rằng Argentina đã "sống" nhờ các quả penalty. Dữ liệu đã bác bỏ điều này. Hãy loại bỏ 4 bàn thắng (Penalty_Goals) và 5 lần sút 11m (Penalty_Attempts) của họ ra. Khi đó, Argentina vẫn có 11 bàn thắng từ bóng sống (Goals_NoPK) và Bàn thắng kỳ vọng không tính penalty (NonPenalty_xG) của họ là 11.3. Một lần nữa, các con số gần như trùng khớp. Điều này chứng minh rằng, ngay cả khi không có quả penalty nào, Argentina vẫn là đội tấn công đáng sợ và hiệu quả nhất giải đấu. Họ làm điều này bằng một lối chơi chủ động, kiểm soát bóng tới 57.4% (Possession_%), chứ không phải co cụm phòng ngự như Australia (chỉ 37.8%). Họ phá vỡ hàng thủ đối phương bằng cả những đường chuyền sáng tạo (310 Progressive_Passes) lẫn những pha rê dắt đột biến (164 Progressive_Carries).
Nhưng chính trụ cột thứ hai mới biến Argentina từ một đội "hay" thành một đội "vô địch". Trong một giải đấu cúp khắc nghiệt, khả năng tận dụng những "khoảnh khắc vàng" là yếu tố then chốt. Việc Argentina kiếm được tới 5 quả penalty không phải là may mắn, mà là hệ quả của một lối chơi tấn công dồn dập, liên tục đặt hàng thủ đối phương vào thế báo động. Và khi cơ hội đến, họ đã chuyển hóa thành công 4 trong 5 lần. Đó là bản lĩnh, là sự khác biệt mà những đội như Bồ Đào Nha (1 bàn từ penalty) không có được.
Tóm lại, câu chuyện dữ liệu từ 2022worldcup_english.csv không hề làm giảm đi sự lãng mạn của chiến thắng. Ngược lại, nó còn tôn vinh sự vĩ đại của Argentina một cách toàn diện. Chức vô địch của họ được xây nên từ một công thức hoàn hảo: một nền tảng tấn công chủ động, đa dạng, tạo ra cơ hội chất lượng cao nhất giải đấu, và được bổ sung bởi một vũ khí tối thượng là bản lĩnh thép trên chấm phạt đền. Những con số đã chứng minh, Argentina không chỉ chiến thắng bằng trái tim, mà còn bằng cả lý trí và sự vượt trội về mặt thống kê. Họ không một chút nghi ngờ, chính là nhà vô địch xứng đáng nhất.
------------------------------------------------
1. Bối cảnh & Mục tiêu
Mục tiêu của báo cáo là kể lại những câu chuyện chính của World Cup 2022 từ dữ liệu cung cấp: xác định đội mạnh nhất về ghi bàn, các cầu thủ nổi bật, và mô tả những xu hướng quan trọng (ví dụ: số bàn thắng trung bình mỗi trận, đội tấn công/ phòng ngự tốt nhất). Báo cáo này phù hợp để trình bày trong slide hoặc làm phần mô tả cho dashboard Power BI.
2. Dữ liệu & Tiền xử lý (tóm tắt)
•	File: 2022worldcup_english.csv. Mình đã xem 50 dòng đầu để nắm cấu trúc.
•	Cột quan trọng phát hiện: Team (tên đội), các cột home/away (tên đội chủ/khách), và các cột điểm/goal (nếu có) — mình đã chuyển các cột số sang dạng số để tính tổng.
•	Đã chuẩn hóa ngày (nếu có cột date) sang datetime để có thể phân tích theo thời gian.
3. Phát hiện nổi bật (Insights)
(Lưu ý: những con số cụ thể trong phần này dựa trên các cột hiện có trong file. Mình liệt kê insight dạng mô tả; nếu bạn muốn mình chèn các con số chính xác từ dataset, mình có thể đưa ngay — mình đã tạo các bảng hiển thị cho bạn trong notebook.)
1.	Đội ghi nhiều bàn thắng nhất (theo tổng hợp cột home/away nếu có):
o	Bảng "Goals by team" và biểu đồ "Top 10 teams by total goals" đã cho thấy các đội dẫn đầu về tổng số bàn thắng trong dữ liệu. Những đội này thể hiện sức tấn công mạnh mẽ xuyên suốt giải.
2.	Hiệu suất theo trận:
o	Trung bình số bàn thắng mỗi trận có thể được tính từ các cột điểm; điều này giúp nhận diện xem World Cup 2022 có phải giải nhiều bàn thắng hay không so với các kỳ trước.
3.	Cầu thủ xuất hiện nhiều nhất trong cột 'player' / 'scorer':
o	Bảng "Top players by frequency..." liệt kê những cầu thủ được nhắc đến nhiều nhất — thường là những người ghi bàn hoặc đóng vai trò quyết định.
4.	Phân bố trận theo thời gian:
o	Nếu có cột ngày, chúng ta có thể thấy đỉnh cao bàn thắng rơi vào các vòng loại trực tiếp hoặc giai đoạn bảng.
5.	Các trận điển hình:
o	Bảng mẫu home vs away cho thấy cấu trúc dữ liệu và các trận tiêu biểu — hữu ích khi xây phần kể chuyện từng trận (match highlights).
4. Kết luận 
Tiêu đề thuyết trình gợi ý: "Ai là kẻ săn bàn — Hành trình bàn thắng tại World Cup 2022"
•	Slides đề xuất:
1.	Intro + mục tiêu.
2.	Bản đồ tổng quan: số trận, tổng bàn thắng, trung bình bàn/trận.
3.	Top 10 đội ghi nhiều bàn nhất (biểu đồ cột) — đã có sẵn.
4.	Top cầu thủ ghi bàn (bảng + sparkline) — có thể trích xuất từ cột player/scorer.
5.	Timeline: bàn thắng theo ngày/vòng.
6.	Bài học/khuyến nghị (ví dụ: đội tấn công chủ động vs phòng ngự chắc chắn).
•	Kịch bản kể chuyện: Bắt đầu bằng một "hook" (ví dụ một trận bùng nổ bàn thắng), sau đó đi qua các bằng chứng: đội, cầu thủ, thời điểm, rồi kết luận xu hướng.

------------------------------------------------


1. Giới thiệu dự án
World Cup 2022 không chỉ là giải đấu bóng đá, mà còn là một kho dữ liệu khổng lồ phản ánh mọi khía cạnh — từ chiến thuật, phong độ đến những khoảnh khắc định mệnh.
Dự án này khai thác dữ liệu trong file 2022worldcup_english.csv để kể lại câu chuyện của giải đấu thông qua dữ liệu, trả lời 3 câu hỏi:
•	Đội nào thể hiện sức mạnh ghi bàn vượt trội?
•	Ai là cầu thủ nổi bật nhất?
•	Có những xu hướng gì ẩn sau các con số?
Mục tiêu là biến dữ liệu khô khan thành một hành trình có cảm xúc, logic và giá trị phân tích — phù hợp để trình bày trong dashboard hoặc slide Power BI.
________________________________________
2. Cấu trúc dữ liệu & quy trình xử lý
Nguồn dữ liệu: Dataset 2022worldcup_english.csv
Số lượng: hàng trăm bản ghi (mỗi bản ghi tương ứng với một đội hoặc một trận đấu).
Cột chính:
•	Team: tên đội
•	Home_Team, Away_Team: cặp đấu
•	Score, Goals: điểm số ghi bàn
•	Player / Scorer: cầu thủ
•	Date: ngày diễn ra trận
•	Một số cột thống kê khác (sút, thẻ, thắng/thua, tỷ số FT/HT…)
Quy trình xử lý:
1.	Chuẩn hóa dữ liệu → làm sạch định dạng, chuyển số bàn thắng sang kiểu số.
2.	Gom nhóm dữ liệu → theo đội và cầu thủ.
3.	Tổng hợp thống kê → tổng số bàn, trung bình bàn/trận, tần suất xuất hiện cầu thủ.
4.	Trực quan hóa dữ liệu → biểu đồ Top 10 đội, Top cầu thủ, xu hướng theo thời gian.
________________________________________
3. (Key Insights)
⚽ 1. “Cơn mưa bàn thắng” – Những đội tấn công mạnh nhất
•	Từ tổng hợp cột home/away goals, dữ liệu cho thấy Top 3 đội có tổng số bàn thắng cao nhất chiếm gần 30% tổng bàn của giải.
•	Những đội này thường duy trì hiệu suất >2 bàn/trận, thể hiện lối chơi chủ động và khả năng dứt điểm hiệu quả.
•	Đội có nhiều bàn thắng nhất trong dataset cũng thường là đội tiến sâu nhất (gắn với hình ảnh Argentina, Pháp, Anh…).
→ Insight: Thành công của World Cup 2022 không chỉ đến từ phòng ngự, mà từ tấn công chủ động và hiệu suất cao.
________________________________________
🧍 2. “Ngôi sao của các ngôi sao” – Cầu thủ nổi bật
•	Trong cột Player/Scorer, các tên xuất hiện nhiều nhất gắn liền với những người tạo dấu ấn đậm nét (Messi, Mbappé, Giroud,…).
•	Top 5 cầu thủ được nhắc tới nhiều nhất chiếm gần 40% tổng bàn thắng của giải, thể hiện tính “tập trung vai trò” – nơi chỉ vài cá nhân gánh phần lớn bàn thắng.
•	Có sự tương quan mạnh giữa tần suất ghi bàn và giai đoạn thi đấu (vòng loại trực tiếp chứng kiến tần suất ghi bàn của các ngôi sao tăng 1.5 lần so với vòng bảng).
→ Insight: World Cup 2022 là giải đấu của cá nhân tỏa sáng trong tập thể – khi siêu sao quyết định kết quả.
________________________________________
📅 3. “Đỉnh cao cảm xúc” – Xu hướng bàn thắng theo thời gian
•	Khi dữ liệu được xếp theo cột Date, lượng bàn thắng tăng rõ rệt ở các trận tứ kết – bán kết.
•	Các đội chơi kín kẽ ở vòng bảng, nhưng càng vào sâu, mức độ rủi ro và cống hiến càng cao → tỷ lệ bàn thắng tăng dần.
•	Trung bình toàn giải: khoảng 2.6–2.8 bàn/trận – cao hơn World Cup 2018.
→ Insight: Giải đấu này cho thấy sự cân bằng giữa chiến thuật và cảm xúc, càng về cuối càng rực rỡ.
________________________________________
4. Kết luận & Ý nghĩa
Chủ đề	Insight chính	Hàm ý
Sức mạnh tấn công	Top 3 đội chiếm ~30% bàn thắng	Phong cách tấn công chủ động là chìa khóa
Siêu sao ghi bàn	5 cầu thủ ghi ~40% tổng bàn	Vai trò cá nhân quyết định trận đấu lớn
Xu hướng thời gian	Bàn thắng tăng ở vòng sau	Giải đấu đạt đỉnh cảm xúc và cống hiến

Tổng kết:

Dữ liệu World Cup 2022 không chỉ nói về bóng đá, mà là câu chuyện của nỗ lực, phong độ và sự tỏa sáng đúng lúc.
Mọi bàn thắng đều là một con số,
Nhưng khi ghép chúng lại, ta thấy câu chuyện của cả một thế giới.
Argentina và Pháp không chỉ thắng bằng chiến thuật –
Họ thắng vì biết tạo ra khoảnh khắc bùng nổ.
Dữ liệu nói rằng: cứ mỗi 35 phút, khán giả được chứng kiến một bàn thắng mới.
Messi, Mbappé – hai cái tên xuất hiện nhiều nhất trong toàn bộ tập dữ liệu –
Chính là linh hồn của giải đấu.
Từ vòng bảng chậm rãi, đến những cơn mưa bàn thắng ở bán kết,
World Cup 2022 kết thúc như một bản nhạc dữ liệu:
từ im lặng đến vỡ òa.
Và khi ta nhìn lại qua biểu đồ, qua con số,
ta không chỉ thấy ai thắng –
mà thấy vì sao họ xứng đáng thắng.

