# [Sentiment Analysis] Sung Si-kyung vs. Jang Beom-june

(Korean title: [Sentiment Analysis] 감성분석을 활용하여 알아보는 성시경 vs.장범준 논란의 '주관적인' 승자는?)

* On a South Korean website, there was a heated discussion on the topic 'Which one of Sung Si-kyung or Jang Beom-june is a greater artist than the other?'. Below are ones of their most hit songs.
    * Sung Si-kyung: "On the road" https://youtu.be/v_K4tnMYsn4?t=54
    * Jang Beom-june: "Cherry blossom ending" https://www.youtube.com/watch?v=tbJX9f2MYPs
* Obviously, there is no way to objectively decide who is better because it's really a matter of personal musical preference.
    * Personally, I'm a fan of Sung :)
* In this notebook, we try to determine which one of the two artists the users of the website prefer 'subjectively' using the sentiment analysis.

* This notebook proceeds as follows:
    * Data preprocessing
    * Sentiment analysis (by **Naver's CLOVA Sentiment API**)
        * https://www.ncloud.com/product/aiService/clovaSentiment
    * Result:

        * |index|artist|positive|negative|sent\_score|
          |---|---|---|---|---|
          |0|Sung Si-kyung|49\.473159327852535|67\.63758043738649|42\.24|
          |1|Jang Beom-june|65\.950075205031|88\.12241754940153|42\.8|
        
    * Word clouds
        * ![Sung's word cloud](./outputs/D12_sung_wordcloud.jpg) ![Jang's word cloud](./outputs/D12_jang_wordcloud.jpg) 


* Again, this analysis is for purely entertainment purposes only! They are both great artists loved by a lot of Korean people.
    
* I hope you enjoy this notebook!
