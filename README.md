# InClass-Arrays

//In-Class: Arrarys

//Examples based on Unity Video & Preston's Notes

using UnityEngine;
using System.Collections;

public class Arrays : MonoBehaviour
{
    int[] myIntArray = {93, 42, 2, 789, 9000}

    void Start ()
    {
        myIntArray[0] = 69;
    }
}

{
    public GameObject[] players;

    void Start()
    {
        players = GameObject.FindGameObjectsWithTag("Player");

        for(int i = 0; i < players.Length; i++)
        {
            Debug.Log("Player Number "+i+" is named "+players[i].name);
        }
    }
}

{
    int[] myIntArray = new int[5];

    void Start ()
    {
        myIntArray[0] = 22;
        myIntArray[1] = 35;
        myIntArray[2] = 12;
        myIntArray[3] = 7;
        myIntArray[4] = 99;
    }
}

{
    int[] myIntArray = new int[5];

    void Start ()
    {
        myIntArray[0] = Spider;
        myIntArray[1] = Slime;
        myIntArray[2] = Snake;
        myIntArray[3] = Crock;
        myIntArray[4] = Mimic;
    }
}

{
    int[] myIntArray = {Spider, Slime, Snake, Crock, Mimic}

    void Start ()
    {
        myIntArray[4] = Troll;
    }
}

//More Examples

public class Fruits : MonoBehaviour

    int[] myFruits = {Apple, Banana, Cherry, Orange, Grape};
    int randomNum = {0, 4};
    
    //print Random.Range [0, 4];
