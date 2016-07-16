#react-native-loadimage

是一款图片预加载插件,带有原生loading加载器,通常在列表显示时,没有一个loading,总是不是很好的感觉,所以封装了一个,自己的项目也在用

install
-----------------------------------------------------
npm install --save loadimage


code
-----------------------------------------------------
<pre>
import Loadimage from 'react-native-loadimage';
export default class extends Component {
render(){
return(
<View style={styles.list}>
<Loadimage style={styles.pic} url='pic.png'/>
<Text style={styles.title}>test</Text>
</View>
)
}

}
const styles = StyleSheet.create({
list: {
backgroundColor: '#fff', marginBottom: 10
},
title: {color: '#666', padding: 10},
pic: {
height: 180
}
});
</pre>

version
-----------------------------------------------------
v0.0.7 update
