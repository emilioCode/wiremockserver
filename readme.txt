WireMock Server APIs:
 
Start recording:
POST: ttp://localhost:9000/api/v1/mock-apis/{{wireMockId}}/__admin/recordings/start
 
Body:
{
    "targetBaseUrl": "baseUrl",
    "extractBodyCriteria": {
        "textSizeThreshold": "0",
        "binarySizeThreshold": "0"
    }
}
 
Stop recording:
POST: http://localhost:9000/api/v1/mock-apis/{{wireMockId}}/__admin/recordings/stop