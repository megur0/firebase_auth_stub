
# This is a private package

# このパッケージの目的
* Firebaseに関わるテストをする際に汎用的に利用可能なスタブを定義したパッケージ

# スタブのベースとなるクラス
* 以下のクラスを定義。すべての実装はException("not implemented")としている。
* 元クラスのコンストラクタがプライベートになっているためextendsはできないためこれらのクラスを用意した。
* FirebaseUserStubBase
    * Userを実装
* UserCredentialStubBase
    * UserCredentialを実装