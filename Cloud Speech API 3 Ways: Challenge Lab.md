export ZONE=$(gcloud compute instances list lab-vm --format 'csv[no-heading](zone)')
gcloud compute ssh lab-vm --project=$DEVSHELL_PROJECT_ID --zone=$ZONE --quiet
__________________________________________________________________________________________________________________
create api - https://console.cloud.google.com/apis/credentials

export API_KEY=
export task_2_file_name=""
export task_3_request_file=""
export task_3_response_file=""
export task_4_sentence=""
export task_4_file=""
export task_5_sentence=""
export task_5_file=""

____________________________________________________________________________________________________________________
curl -LO raw.githubusercontent.com/lturcot4/creativejv/refs/heads/main/arc132.sh
sudo chmod +x arc132.sh

./arc132.sh
