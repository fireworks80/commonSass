    / abstracts (mixins, function, variables....)
    / base (helper, reset, font)
    / vender (normalize....)

이 외 필요한 파일 및 폴더는 각자 생성해서 사용. 

class name 앞에 사용하고 있는 클래스의 폴더명을 prefix로 붙여 준다.(선택)
ex) .h: helper파일
    .h-a11y-hidden {
        ........
    }

reset, mixin, vender는 따로 붙일 필요 없음
그 외 사용자 class는 prefix를 붙아면 추후 수정시 class의 위치를 좀더 빠르게 파악 할 수 있다고 생각함

common으로 사용 할 코드 추가 부탁드립니다.