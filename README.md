# Museum-Galeri-Nasional

#Pembuatan Player Virtual Reality

void Start()
    {        cc = GetComponent<CharacterController>();      }

    void Update()
    {
        if (Virtual RealityCamera.eulerAngles.x >= toggleAngle &&Virtual RealityCamera.eulerAngles.x < 90.0f)
        {
            moveForward = true;         }
        else
        {             moveForward = false;        }
      



  if (moveForward)
  Vector3 forward = Virtual RealityCamera.TransformDirection(Vector3.forward);

            cc.SimpleMove(forward * speed);
        }
    }
}



