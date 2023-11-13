<template>
     <div id="deepbeyond">
          <p class="text-4xl my-3 font-bold">Deep Beyond</p>
          <img src="@/assets/deepbeyond.png" alt="Deep Beyondアイコン" class="my-3 w-80 mx-auto" loading=”lazy”>
          <p class="text-lg font-bold my-2">概要・開発目的</p>
          <p>馬の写真から自動で馬体測定をするソフトウェア。競馬好きの先輩がサラブレッドの足の長さと成績が
          関係しているという噂を検証することからスタートし、最終的には馬の健康状態測定にも使えるのではないかと
          している。
          </p>
          
          <p class="text-lg font-bold my-2">開発</p>
          <p>先輩二人と同級生一人と私の四人で開発し、元々pythonで書かれていたコードをKotlinに変換しAndroid上で動くようにした。
          Semantic Segmentationにより、写真から馬体を切り取り各部位の測定を行う。
          </p>

          <p class="text-lg font-bold my-2">工夫点</p>
          <p>
          </p>

          <p class="text-lg font-bold my-2">苦労点</p>
          <p>pythonからKotlinに変換する際に配列の扱い方やopencvの使い方に違いが多く、エラーが多発した。
          </p>

          <p class="text-lg font-bold my-2">改善案</p>
          <p>馬の写っていない写真を検出した際のエラー処理
          </p>

          <p class="text-lg font-bold my-2">リンク</p>
          <a href="https://github.com/deep-beyond/deep-beyond-android"
               class="url-link"> https://github.com/deep-beyond/deep-beyond-android</a>
     </div>
</template>