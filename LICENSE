import { StyleSheet, Text, View, Image, TextInput, TouchableOpacity } from 'react-native';
import AntDesign from '@expo/vector-icons/AntDesign';

export default function App() {
  return (
      <View style={styles.container}>
      <View style={styles.viewHeader}>

      <AntDesign name="menu" size={24} color="white" />
      <Text style={styles.textHeader}>TEC FILMES</Text>


      <TouchableOpacity>

      </TouchableOpacity>
      </View>



      <View style = {styles.containerSearch}>

        <TextInput 
        placeholder='Digite o filme que deseja buscar'
        style = {styles.inputSearch}
        ></TextInput>

        <TouchableOpacity>
        <AntDesign name="search" size={24} color="black" />
        </TouchableOpacity>

      </View>


      <Text style = {styles.textBanner}> Em cartaz </Text>

      <Image
      source={require("./assets/os-velozes-e-furiosos.jpg")}
      style = {styles.imageBanner}
      ></Image>


      </View>
  );
}

const styles = StyleSheet.create({

  container: {
    flex: 1,
    backgroundColor: '#171A4A',
    alignItems: 'center',
   
  },

  viewHeader: {
    flexDirection: 'row',
    width:'90%',
    alignItems:'center',
    marginTop: 10,
    justifyContent:'space-between'
  },

  textHeader: {
    fontSize: 25,
    color: 'white',
    fontWeight: 'bold',
  },

  containerSearch: {
    marginTop: 20,
    width: "90%",
    backgroundColor: 'white',
    borderRadius: 5,
    padding: 8,
    flexDirection: 'row',
    justifyContent: 'space-between',
    alignItems: 'center',
  },

  inputSearch: {
    height: 40,
    padding: 4,
    width: '100%',
  },

  imageBanner: {
    width: '85%',
    height: 200,
    marginTop: 15,
    borderRadius: 10,
  },
  
  textBanner: {
    color: 'white',
    width: '90%',
    fontSize: 25,
    marginTop: 25,
    fontWeight: 'bold',
  }

});
